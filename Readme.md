*This repository is a mirror of the [component](http://component.io) module [stagas/async-map](http://github.com/stagas/async-map). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/stagas-async-map`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# async-map

asynchronous map

## Installation

```sh
$ component install stagas/async-map
```

## Usage

#### map(array, fn, callback)

## Example

```js
var map = require('async-map');

map([1, 2, 3], function(el, fn){
  fn(null, el + 1);
}, function(err, res){
  console.log(res); // [2, 3, 4]
});
```

## License

MIT
