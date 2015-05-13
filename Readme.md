
# after-transition

[![Join the chat at https://gitter.im/anthonyshort/after-transition](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/anthonyshort/after-transition?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

  Fire a callback after a transition or immediately if the browser does not support transitions.
  If the element does not have a transition property it will also fire immediately.

## Installation

    $ component install anthonyshort/after-transition

or via npm for use with Browserify

    $ npm install after-transition

## API

    var afterTransition = require('after-transition');

    afterTransition(el, function(){
      // Do things when the transition has finished
      // This will fire immediately for IE
    });

    afterTransition.once(el, function(){
      // Same as above but will only fire once
    });

## License

  MIT
