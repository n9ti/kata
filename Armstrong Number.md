# Armstrong Number

Given integer. Your function should return it is Armstrong number or not.
An Armstrong number of three digits is an integer such that the sum of the cubes of its digits is equal to the number itself

ก็คือตัวเลขที่ แต่ละหลักยกกำลังด้วยความยาว + กันทั้งหมดต้องได้ค่าเท่ากับตัวเอง

```
6   => 6^1 = 6                true
12  => 1^2 + 2^2 = 5          false
13  => 1^2 + 3^2 = 10         false
371 => 3^3 + 7^3 + 1^3 = 371  true
```

```js
const test = require('ava')
const isArmstrongNumber = require('./isArmstrongNumber')

test('isArmstrongNumber', function (t) {
  t.is(isArmstrongNumber(6, true))
  t.is(isArmstrongNumber(11, false))
  t.is(isArmstrongNumber(1634, true))
})
```
