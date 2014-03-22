*This repository is a mirror of the [component](http://component.io) module [eldargab/load-script](http://github.com/eldargab/load-script). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/eldargab-load-script`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*
# load-script

Dynamic script loading.

## Installation

via component

```
$ component install eldargab/load-script
```

via npm

```
$ npm install load-script
```

## API

```javascript
var load = require('load-script')

load('foo.js', function (err) {
  if (err) {
    // print useful message
  }
  else {
    // use script
    // note that in IE8 and below loading error wouldn't be reported
  }
})
```

## License

MIT
