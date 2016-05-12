# get-title-at-url

[![Dependency Status](https://david-dm.org/m4bwav/get-title-at-url.svg)](https://david-dm.org/m4bwav/get-title-at-url)

Npm package to retrieve the title at a given url.  Largely combines articleTitle with request.


## Installation

Installation is easiest through npm:

`npm install get-title-at-url --save`


## Usage

**get-title-at-url** can be included as reference.

```
var getTitleAtUrl = require('get-title-at-url');

getTitleAtUrl(url, function(title){
  console.log(title);
});
```

## CLI

```
$ npm install --global get-title-at-url
```

```
$ get-title-at-url --help

  Usage
    $ get-title-at-url "<url>"

  Example
    $ get-title-at-url "http://www.google.com"
```


## License

MIT © [Mark Rogers](http://www.markdavidrogers.com)