## Running JavaScript:

- We can run JavaScript from the browser's console.

- Also we can run it using `script` tag:

```javascript
<script>console.log('Heyyy');</script>
```

It is better to keep `script` tag before the closing `body` tag, because we can access the HTML elements written above the `script` tag as they are above the JS.

- Also, we can run JavaScript in another file using `script` tag with `src` attribute:

```javascript
<script src="relative path to js file"></script>
```

- Another way to run it via Node.js - instead of running in the context of a website we run it in an actual machine. In console, run: `node file.js`
