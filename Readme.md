*This repository is a mirror of the [component](http://component.io) module [component/color-parser](http://github.com/component/color-parser). It has been modified to work with NPM+Browserify. You can install it using the command `npm install npmcomponent/component-color-parser`. Please do not open issues or send pull requests against this repo. If you have issues with this repo, report it to [npmcomponent](https://github.com/airportyh/npmcomponent).*

# color-parser

  CSS color string parser

## Installation

    $ component install component/color-parser

### Example

```js
var parse = require('color-parser');

parse('#fc0')
// => { r: 255, g: 204, b: 0, a: 1 }

parse('#ffcc00')
// => { r: 255, g: 204, b: 0, a: 1 }

parse('rgb(255, 204, 0)')
// => { r: 255, g: 204, b: 0, a: 1 }

parse('rgba(255, 204, 0, 1)')
// => { r: 255, g: 204, b: 0, a: 1 }
```

# License

  MIT
