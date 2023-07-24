# Tower Builder Code Challenge

## Description

This code challenge requires you to create a function that builds a tower of '*' with a specified number of floors. The tower will be represented as an array of strings, where each string represents a floor of the tower.

The tower is built with the following pattern:

- The first floor has 1 block.
- The second floor has 3 blocks.
- The third floor has 5 blocks.
- The pattern continues, with each subsequent floor having 2 more blocks than the previous floor.

For example, a tower with 3 floors looks like this:

```
[
    '  *  ',
    ' *** ',
    '*****'
]
```

And a tower with 6 floors looks like this:

```
[
    '     *     ',
    '    ***    ',
    '   *****   ',
    '  *******  ',
    ' ********* ',
    '***********'
]
```

## How to Use

The function is implemented in JavaScript. To use it, follow these steps:

1. Copy the provided `towerBuilder` function into your JavaScript environment (e.g., a JavaScript file, browser console, or Node.js).
2. Call the `towerBuilder` function, passing the desired number of floors as an argument.
3. The function will return the tower as an array of strings, where each string represents a floor of the tower.

```javascript
// Example usage
const tower3Floors = towerBuilder(3);
console.log(tower3Floors);

const tower6Floors = towerBuilder(6);
console.log(tower6Floors);
```

## Function Signature

```javascript
function towerBuilder(n) {
  // Function implementation
}
```

- `n`: An integer representing the number of floors in the tower.

## Test Cases

Below are some test cases to verify the correctness of the `towerBuilder` function:

```javascript
console.log(towerBuilder(1));
// Output: ['*']

console.log(towerBuilder(4));
// Output:
// [
//   '   *   ',
//   '  ***  ',
//   ' ***** ',
//   '*******'
// ]
```

## License

This code challenge is open-source under the MIT License. Feel free to use, modify, and distribute it as needed.

