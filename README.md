# three-mtl-loader


The three.js mtl loader as a module

## Usage

```javascript
var THREE = require('three');
var MTLLoader = require('three-mtl-loader')(THREE);
var mtlLoader = new MTLLoader();
mtlLoader.setPath('./path/to/assets/');
mtlLoader.load('model.mtl', function(matl) {
  //do something with matl
});
```
