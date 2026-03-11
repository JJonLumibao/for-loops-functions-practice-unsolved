# ARRAY FLAT

The **flat()** creates a new array with all sub-array elements concatenated into it recursively up to the specified depth.

```JS
const arr1 = [0, 1, 2, [3, 4]];
console.log(arr1.flat());
// expected output: Array [0, 1, 2, 3, 4]
```

For this exercise we want you to build a flatArrays() function that solves the same task
for the depth of 1 with **for loops ONLY**.

**The flatArrays() function should:**

- Take an array as the argument.
- The array might include items of any type: numbers, strings, booleans, or arrays.
- Return a single array of all the array's items.

## Example:

```JS
flatArrays([['a', 'b'], 'c', 'd', ['e', 'f', 'g'], 'h']);
// Expected output: ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h']
```

## Learn more

[Array flat() docs](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Array/flat)
