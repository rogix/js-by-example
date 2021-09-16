# js-by-example

## Arrays

Reduce:

Sum all values of an array

```js

let total = [ 0, 1, 2, 3 ]

total.reduce(
  ( previousValue, currentValue ) => previousValue + currentValue,
  0
)

// total is 16
```
