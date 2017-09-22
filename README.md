Rollbarjs jQuery
=========

If you use jQuery 1.7+ and have it installed via webpack, this will instruct jQuery to wrap any functions passed into jQuery's ready(), on() and off() to catch errors and report them to Rollbar. 

Be sure to include this after the jQuery is loaded

## Installation

  npm install rollbarjs-jquery --save

## Usage

  var rollbarjs-jquery = require('rollbarjs-jquery');

## Contributing

In lieu of a formal styleguide, take care to maintain the existing coding style.
Add unit tests for any new or changed functionality. Lint and test your code.

## Release History

* 0.1.0 Initial release