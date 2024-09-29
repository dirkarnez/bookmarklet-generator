```js
const generator = code => `javascript:${window.encodeURI(`(function(){${code}})()`)}`
```
