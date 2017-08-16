# Remove Duplicates from Sorted Array

Given a sorted array, delete all duplicates such that each element appear only once.

```
For example,
Given [1, 1, 2], return [1, 2].
Given [1, 1, 2, 3, 3, 3, 4], return [1, 2, 3, 4]
```

```js
const test = require('ava')
const removeDuplicates = require('./removeDuplicates')

test('removeDuplicates', function (t) {
  t.deepEqual(removeDuplicates([]), [])
  t.deepEqual(removeDuplicates([1, 1, 1]), [1])
  t.deepEqual(removeDuplicates([1, 1, 2]), [1, 2])
  t.deepEqual(removeDuplicates([1, 1, 2, 3, 3, 3, 4]), [1, 2, 3, 4])
})
```
