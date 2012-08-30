twilio-client-token
===================

Create Twilio Client capability token for Node.js apps

Usage:
```
var TwilioCapability = require('twilio-client-token');

var tc = new TwilioCapability('ACxxx', 'yyy');

tc.allowClientOutgoing('APzzz');

var token = tc.generate();
```
