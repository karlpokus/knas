[![Build Status](https://travis-ci.org/karlpokus/knas.svg?branch=master)](https://travis-ci.org/karlpokus/knas)
[![npm version](https://badge.fury.io/js/knas.svg)](https://badge.fury.io/js/knas)

# knas
Simple Error class for node.js Forked from [this](https://github.com/guillaumervls/client-error).

# Install
```
$ npm install knas
```

# Usage
```javascript
var Knas = require('knas');

// in middleware
return next(new Knas(401, "invalid key")); // defaults to 401, "Bad request"
```

# test
```
$ npm test
```

# Licence
```
The MIT License (MIT)

Copyright (c) 2014 guillaumervls

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of
the Software, and to permit persons to whom the Software is furnished to do so,
subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS
FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR
COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER
IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN
CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
```
