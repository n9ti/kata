# Calculate BMI

Write function bmi that calculates body mass index (bmi = weight / height ^ 2).

```
if bmi <= 18.5 return "Underweight"

if bmi <= 25.0 return "Normal"

if bmi <= 30.0 return "Overweight"

if bmi > 30 return "Obese"
```

```js
const test = require('ava')
const calculateBMI = require('./calculateBMI')

test('calculateBMI', function (t) {
  t.is(calculateBMI(45, 1.76), 'Underweight')
})
```
