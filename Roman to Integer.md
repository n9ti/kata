# Roman to Integer

Given a roman numeral, convert it to an integer.
Input is guaranteed to be within the range from 1 to 3999.

```js
const test = require('ava')
const romanToInt = require('./romanToInt')

test('romanToInt', function (t) {
  t.is(romanToInt('I'), 1)
  t.is(romanToInt('IV'), 4)
  t.is(romanToInt('XI'), 11)
  t.is(romanToInt('MMMCMXCIX'), 3999)
})
```
