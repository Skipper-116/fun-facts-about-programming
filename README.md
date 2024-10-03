# Fun Facts About Programming

A simple npm package that provides random fun facts about programming. This package includes at least 1000 interesting, quirky, and educational facts about programming.

## Installation

You can install the package using npm:

```bash
npm install fun-facts-about-programming
```

Or you can install it globally:

```bash
npm install -g fun-facts-about-programming
```

## Usage

To use the package, import it and call the `getRandomFact` function to get a random programming fun fact.

### Example

```javascript
const { getRandomFact } = require('fun-facts-about-programming');

console.log(getRandomFact());
```

### Output

```
The first computer programmer was Ada Lovelace.
```

## Testing Locally

To test the package locally before publishing, you can create a simple script:

```bash
touch test.js
```

Then add the following content to `test.js`:

```javascript
const { getRandomFact } = require('./index');

console.log(getRandomFact());
```

Run the test file:

```bash
node test.js
```

## License

This package is licensed under the MIT License.