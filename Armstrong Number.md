# Armstrong Number

Given integer. Your function should return it is Armstrong number or not.
An Armstrong number of three digits is an integer such that the sum of the cubes of its digits is equal to the number itself

```
6   => 6<sup>1</sup> = 6                                    true
12  => 1<sup>2</sup> + 2<sup>2</sup> = 5                    true
371 => 3<sup>3</sup> + 7<sup>3</sup> + 1<sup>3</sup> = 371  true
```

```js
const test = require('ava')
const isArmstrongNumber = require('./isArmstrongNumber')

test('isArmstrongNumber', function (t) {
  t.is(isArmstrongNumber(6, true)
  t.is(isArmstrongNumber(11, false)  
  t.is(isArmstrongNumber(1634, true)  
})
```
