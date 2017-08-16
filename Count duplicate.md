# Count Array

Given array of integer. You should count how many it appear array.

```js
const test = require('ava')
const countArray = require('./countArray')

test('countArray', function (t) {
  t.is(countArray([1, 1, 2, 3, 5, 5, 5], {
      1: 2,
      2: 1,
      3: 1,
      5: 3
  })

  t.is(countArray([2, 3, 4], {
      2: 1,
      3: 1,
      4: 1
  })
})
```
