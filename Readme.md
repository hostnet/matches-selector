# matches-selector

Check if an element matches a given selector.  For use with browserify.

[![Dependency Status](https://gemnasium.com/ForbesLindesay/matches-selector.png)](https://gemnasium.com/ForbesLindesay/matches-selector)
[![NPM version](https://badge.fury.io/js/matches-selector.png)](http://badge.fury.io/js/matches-selector)

## Installation

    $ npm install matches-selector

## Example

```js
var matches = require('matches-selector');
matches(el, 'ul li a');
// => true or false
```

## Running Tests

Tests can be run locally using testling:

```
npm install browserify -g
npm install testling -g
testling
```

## License

  MIT
