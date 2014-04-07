#parse-bites
> Parse file size into an object, inspired by [parse-ms](https://github.com/sindresorhus/parse-ms)

##install
```bash
$ npm install parse-bites --save
```

##Usage
```js
var parseBites = require("parse-bites");
parseBites(3003, true);
//=> { b: 3, kb: 3, mb: 0, gb: 0, tb: 0, pb: 0 }
```

## License
[MIT](http://opensource.org/licenses/MIT) © [Jarvys](http://jarvys.github.io)
