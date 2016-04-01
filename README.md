# roots jade loader
A [webpack](http://webpack.io) loader for use within [roots-mini](https://github.com/carrot/roots-mini)

## Usage

```js
const template = require('jade!./file.jade')
// => returns file.jade content as string of JSON (via JSON.stringify)
// roots-mini uses JSON.parse() internally to decode
```

[Webpack Documentation: Using loaders](http://webpack.github.io/docs/using-loaders.html)

## License & Acknowledgements

- License: [MIT](http://www.opensource.org/licenses/mit-license.php)
- This project was based of the original work of [@webpack/jade-loader](https://github.com/webpack/jade-loader)
