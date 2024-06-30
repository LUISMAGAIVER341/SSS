# SSS
Simple StyleSheet

# Documentation
## Quick Start
To start use 
```bash
  npm init
```
(This creates the package)

And then, just
```bash
  npm install simple-stylesheet
```

(This installs SSS)

Add this to your js code:
```javascript
  import sss from "./node_modules/simple-stylesheet/index.js";

  sss.start();
```

(imports, and then start)

In the `html`, link the js file by the following piece of code:
```html
  <script type="module" src="path/to/file.js"></script>
```

## Methods

`top`: usage: sss.top("The id of your element", "The value");  <-- This is the distance between
