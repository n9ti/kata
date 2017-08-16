# Integer to Roman

Given a integer, convert it to an roman numeral.
Input is guaranteed to be within the range from 1 to 3999.

```js
const test = require('ava')
const intToRoman = require('./intToRoman')

test('intToRoman', function (t) {
  t.is(intToRoman(1), 'I')
  t.is(intToRoman(4), 'IV')
  t.is(intToRoman(11), 'XI')
  t.is(intToRoman(3999), 'MMMCMXCIX')
})
```
