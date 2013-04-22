# nodeDocker
node.js client API for Docker.io

## Features
* Call Docker methods from node.js

##Supported Methods
* ps
* inspect
* port
* run

### Examples
Just a few examples:
```js
var nd = require('../lib');
nd.init('/bin/');
```