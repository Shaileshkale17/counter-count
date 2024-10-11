# counter-count

This is a simple counter module that increments a count each time the `counter` function is called. The counter starts from `-1` and increments by `1` with each invocation.

## Getting Started

### Prerequisites

- Node.js installed on your system.

### Installation

1. Clone the repository or download the `counter.js` file.
2. In the directory where `counter.js` is located, create a `package.json` file by running:

   ```bash
   npm init -y
   ```

3. Ensure that `counter.js` is properly exported and ready to use in your application.

### Usage

1. Import the module in your JavaScript file.

   ```javascript
   const counter = require("./counter");
   ```

2. Call the `counter` function to increment the count:

   ```javascript
   console.log(counter()); // Output: 0
   console.log(counter()); // Output: 1
   console.log(counter()); // Output: 2
   ```

### How it works

- The counter starts at `-1` and increments each time the `counter` function is called.
- The `count` is stored in a closure, so it maintains its state between function calls.

### Example

```javascript
const counter = require("./counter");

console.log(counter()); // Output: 0
console.log(counter()); // Output: 1
console.log(counter()); // Output: 2
```
