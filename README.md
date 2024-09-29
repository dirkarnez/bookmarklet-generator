bookmarklet-generator
=====================
```js
const generator = code => `javascript:${window.encodeURI(`(function(){${code}})()`)}`
```

### TODOs
- [ ] webpack bundle external dependencies therefore there will not be CORS issue
- [ ] css inject?

### References
- https://mrcoles.com/bookmarklet/
