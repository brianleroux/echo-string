# echo-string

a module for echoing a value as a string

## install

    npm i echo-string

### usage

You can consume this module from vanilla Node:

```javascript
var echo = require('echo-string')

console.log(echo('hello'))
```

Or any other env that supports ES5 like CoffeeScript:

```coffeescript
echo = require 'echo'

console.log echo('hello')
```

Or even ES6:

```javascript
import echo from 'echo-string'

console.log(echo('hello'))
```

### contrib notes

- `npm test` builds and runs the tests
- `npm run build` builds `./src` to `./dist/index.js`
- `npm run debug` compiles `./src` with sourcemaps to `./dist/index.js`
- `npm publish .` would publish `./dist/index.js` to the configured npm registry
