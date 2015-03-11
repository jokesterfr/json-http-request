# json-http-request

A JSON speaking HTTP request handler

## Usage

This script is intended to be used *browser-side*:

```html
<script src="./json-http-request.js"></script>
```

Then you can use it this way:

```javascript
// Instanciate new request with callback
var req = new JSONHttpRequest(function (err, data) {
    console.log(err, data);
});

// Open and send request
req.open('GET', '/api/users');
req.send(null);
```

## Licence

The MIT License (MIT) applies here.

Copyright (c) 2015 Clément Désiles
