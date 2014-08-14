# default-browser-id [![Build Status](https://travis-ci.org/sindresorhus/default-browser-id.svg?branch=master)](https://travis-ci.org/sindresorhus/default-browser-id)

> Get the [bundle identifier](https://developer.apple.com/library/Mac/documentation/General/Reference/InfoPlistKeyReference/Articles/CoreFoundationKeys.html#//apple_ref/doc/plist/info/CFBundleIdentifier) of the default browser (OS X)  
> Example: `com.apple.Safari`


## Install

```sh
$ npm install --save default-browser-id
```


## Example

```js
var defaultBrowserId = require('default-browser-id');

defaultBrowserId(function (err, browserId) {
	console.log(browserId);
	//=> com.apple.Safari
});
```


## CLI

```sh
$ npm install --global default-browser-id
```

```sh
$ default-browser-id --help

  Example
    default-browser-id
    com.apple.Safari
```


## License

MIT © [Sindre Sorhus](http://sindresorhus.com)
