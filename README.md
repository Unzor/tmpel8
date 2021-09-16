# templ8
A template maker for NodeJS.

# Example
index.js:
```javascript
var templ8 = require('templ8-maker');

templ8.use('index.tmpl8', {
	demo: process.env.app_secret,
	settings: {
		path: '/'
	}
});
```

index.tmpl8:
```html
<h1> ${templ8.demo} </h1>
```
