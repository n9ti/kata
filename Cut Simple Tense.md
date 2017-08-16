# cut simple tense

Given a sentences, find present simple tense like "is", "am", "are"</br>
and return word without these word

```js
const test = require('ava')
const cutSimpleTense = require('./cutSimpleTense')

const cut = ['is', 'am', 'are']

test('cut Simple Tense', function (t) {
  t.is(cutSimpleTense('Mary is happy', cut), 'Mary happy')
  t.is(cutSimpleTense('Winter is coming', cut), 'Winter coming')
  t.is(cutSimpleTense('How are you', cut), 'How you')
  t.is(cutSimpleTense('I am Joey, This is an area 51 there are have a lot of camera inside', cut),
  'I Joey, This an area 51 there have a lot of camera inside')
})
```
