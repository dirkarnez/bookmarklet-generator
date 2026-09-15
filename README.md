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


<!-- Security scan triggered at 2026-09-15 09:32:03 -->