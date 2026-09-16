# Math Utils

A lightweight TypeScript math utility library providing simple and reusable functions for common mathematical operations.

It includes utilities for addition, subtraction, multiplication, division, powers, square roots, absolute values, rounding, and more.

## Installation

Install the package using npm:

```bash
npm install @el-stone/math/math
```

Using Yarn:

```bash
yarn add @el-stone/math/math
```

Using pnpm:

```bash
pnpm add @el-stone/math/math
```

## Usage

Import the functions you need:

```ts
import {
  sum,
  subtract,
  multiply,
  divide,
  power,
  mod,
  sqrt,
  abs,
  round,
  ceil,
} from "@el-stone/math/math";
```

### Addition

```ts
sum(10, 5);
// 15
```

### Subtraction

```ts
subtract(10, 5);
// 5
```

### Multiplication

```ts
multiply(10, 5);
// 50
```

### Division

```ts
divide(10, 5);
// 2
```

### Power

```ts
power(2, 3);
// 8
```

### Modulo

```ts
mod(10, 3);
// 1
```

### Square Root

```ts
sqrt(25);
// 5
```

### Absolute Value

```ts
abs(-10);
// 10
```

### Round

```ts
round(4.6);
// 5
```

### Ceil

```ts
ceil(4.1);
// 5
```

## API

| Function         | Description                                | Example                 |
| ---------------- | ------------------------------------------ | ----------------------- |
| `sum(a, b)`      | Adds two numbers                           | `sum(2, 3)` → `5`       |
| `subtract(a, b)` | Subtracts the second number from the first | `subtract(5, 2)` → `3`  |
| `multiply(a, b)` | Multiplies two numbers                     | `multiply(4, 3)` → `12` |
| `divide(a, b)`   | Divides the first number by the second     | `divide(10, 2)` → `5`   |
| `power(a, b)`    | Raises a number to a power                 | `power(2, 3)` → `8`     |
| `mod(a, b)`      | Returns the remainder of a division        | `mod(10, 3)` → `1`      |
| `sqrt(a)`        | Returns the square root of a number        | `sqrt(25)` → `5`        |
| `abs(a)`         | Returns the absolute value                 | `abs(-8)` → `8`         |
| `round(a)`       | Rounds to the nearest integer              | `round(4.6)` → `5`      |
| `ceil(a)`        | Rounds upward to the nearest integer       | `ceil(4.1)` → `5`       |

## TypeScript Support

This package is written in TypeScript and provides built-in type definitions.

```ts
import { sum } from "@el-stone/math/math";

const result: number = sum(10, 20);

console.log(result);
// 30
```

## Features

- Lightweight
- Written in TypeScript
- Fully typed
- Simple API
- Zero dependencies
- Works with JavaScript and TypeScript
- Suitable for Node.js projects
- Easy to integrate

## JavaScript Usage

The package can also be used with JavaScript:

```js
import { sum, multiply } from "@el-stone/math/math";

console.log(sum(10, 20));
console.log(multiply(5, 4));
```

## Error Handling

JavaScript's native number behavior is preserved.

For example:

```ts
divide(10, 0);
// Infinity
```

and:

```ts
sqrt(-1);
// NaN
```

The library does not currently throw custom errors for these operations.

## Contributing

Contributions are welcome.

If you would like to improve the package, add new mathematical functions, fix bugs, or improve the documentation, feel free to open an issue or submit a pull request.

### Development

Clone the repository:

```bash
git clone https://github.com/your-username/@el-stone/math/math.git
```

Install dependencies:

```bash
npm install
```

Build the package:

```bash
npm run build
```

Run tests:

```bash
npm test
```

## License

This project is licensed under the MIT License.

See the `LICENSE` file for more information.

## Author

Created and maintained by El Stone.

## Support

If you find this package useful, consider giving the project a ⭐ on GitHub.

For bugs, feature requests, or suggestions, please open an issue on the GitHub repository.
