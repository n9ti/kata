# Binary to Decimal

Given a binary, convert it to decimal form.</br>
Input will be only 1 or 0

```js
const test = require('ava')
const binaryToDecimal = require('./binaryToDecimal')

test('binaryToDecimal', function (t) {
  t.is(binaryToDecimal(1001), 9)
  t.is(binaryToDecimal(1101), 13)
  t.is(binaryToDecimal(1111), 15)
  t.is(binaryToDecimal(1010), 10)
})
```
