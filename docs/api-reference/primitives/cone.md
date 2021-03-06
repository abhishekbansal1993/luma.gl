# Cone

Creates a Cone model. Inherits methods from [Model](Model).

Create a white Cone of base radius 2 and height 3.
```js
var whiteCone = new Cone({
  radius: 2,
  height: 3,
  cap: true,
  colors: [1, 1, 1, 1]
});
```

The constructor for the Cone class. Use this to create a new Cone.

`var model = new Cone(gl, options);`

* nradial - (*number*, optional) The number of vertices used to create the disk for a given height. Default's 10.
* nvertical - (*number*, optional) The number of vertices for the height. Default's 10.
* radius - (*number*) The radius of the base of the cone.
* cap - (*boolean*, optional) Whether to put the cap on the base of the cone. Default's false.
