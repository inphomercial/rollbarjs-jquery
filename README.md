Rollbarjs jQuery
=========

If you use jQuery 1.7+ and have it installed via webpack, this will instruct jQuery to wrap any functions passed into jQuery's ready(), on() and off() to catch errors and report them to Rollbar. 

Be sure to include this after jQuery is loaded.

Reference https://rollbar.com/docs/notifier/rollbar.js/#jquery

## Installation

  npm install rollbarjs-jquery --save

## Usage

  var rollbarjs-jquery = require('rollbarjs-jquery');

## Release History

* 0.1.0 Initial release