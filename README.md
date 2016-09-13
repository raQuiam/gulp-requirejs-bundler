# gulp-requirejs-bundler

A require-bundler plugin for [gulp](https://github.com/wearefractal/gulp)

## Usage

First, install `gulp-requirejs-bundler-with-baseurl` as a development dependency:

```shell
npm install --save-dev gulp-requirejs-bundler-with-baseurl
```

Then, add it to your `gulpfile.js`:

```javascript
var require-bundler = require("gulp-requirejs-bundler-with-baseurl");

gulp.src("./src/*.ext")
	.pipe(require-bundler({
		msg: "Hello Gulp!",
		bundleUrl: "/scripts"
	}))
	.pipe(gulp.dest("./dist"));
```

## API

### require-bundler(options)

#### options.msg
Type: `String`  
Default: `Hello World`

TODO: API details to be documented here.


## License

[MIT License](http://en.wikipedia.org/wiki/MIT_License)
