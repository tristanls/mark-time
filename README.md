# mark-time

_Stability: 3 - [Locked](https://github.com/tristanls/stability-index#stability-3---locked)_

Mark high resolution time as floating point milliseconds (valid up to six decimal places).

## Usage

```javascript
var markTime = require('mark-time');

var startTime = markTime();
var stopTime = markTime();
console.log(startTime, stopTime, stopTime - startTime);
```
