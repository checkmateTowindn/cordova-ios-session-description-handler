# cordova-ios-session-description-handler
A Session Description Handler (SDH) for SIP.js, that supports the Cordova iOS WebRTC API.


## Installation

```javascript
npm install --save cordova-ios-session-description-handler
```

## Usage

```javascript
const CordovaIOSSDH = require('cordova-ios-session-description-handler').default;

const config = {};

...
config.sessionDescriptionHandlerFactory = CordovaIOSSDH.factory;
...

const UA = new SIP.UA(config);
```
