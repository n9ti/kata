# Reverse String

Write a function that takes a string as input and returns the string reversed.

```
Example:
Given s = "hello", return "olleh".
```

```js
const test = require('ava')
const reverseString = require('./reverseString')

test('reverseString', function (t) {
  t.is(reverseString(''), '')
  t.is(reverseString('a'), 'a')
  t.is(reverseString('hello'), 'olleh')
})
```
