*This repository is a mirror of the [component](http://component.io) module [yuehu/on-stop](http://github.com/yuehu/on-stop). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/yuehu-on-stop`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# on-stop

  Execute when user stops.

## Installation

  Install with [component(1)](http://component.io):

    $ component install yuehu/on-stop

## API

```js
var stop = require('on-stop');

// stop(el, func, options)

stop(el, function() {
    console.log('stop');
})
```

### Options

1. **duration**: delay duration for an event, default is 400ms
2. **event**: stop on the given event, default is `keyup`
3. **clearEvent**: event for clearTimeout, usually you don't need set this value


## License

  MIT
