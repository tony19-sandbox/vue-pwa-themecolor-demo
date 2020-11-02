> Demo for https://stackoverflow.com/questions/64608853/vue-js-generate-manifest-json-with-env-variables

Configure PWA theme color with an environment variable (e.g., `MY_VARIABLE` in `.env`):

```js
// vue.config.js
module.exports = {
  pwa: {
    themeColor: process.env.MY_VARIABLE,
  }
}
```
