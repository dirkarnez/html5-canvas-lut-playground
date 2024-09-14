html5-canvas-lut-playground
===========================
- [LookupTable – three.js docs](https://threejs.org/docs/#examples/zh/math/Lut)
- [lut/index.js at master · hughsk/lut](https://github.com/hughsk/lut/blob/master/index.js)
  - ```javascript
    function lut(red, green, blue, canvas) {
      var red = red || 32, green = green || 32, blue = blue || 32
    ```
```C
#define LUT_SQUARE_DIM 32
#define LUT_FULL_WIDTH LUT_SQUARE_DIM*LUT_SQUARE_DIM
unsigned char* lut = new unsigned char[LUT_FULL_WIDTH * LUT_SQUARE_DIM * 3];
```
