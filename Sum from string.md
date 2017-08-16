# SUM from string

Write function for sum number from string.

```js
const test = require('ava')
const sumFromString = require('./sumFromString')

test('sumFromString', function (t) {
  t.is(sumFromString('abc2def8ghi'), 10)
  t.is(sumFromString('abc2def18ghi'), 20)
  t.is(sumFromString('abc2def18ghi180'), 200)
})
```
