# @frogebot/canvas
Discord music bot module, designed for FrogeBot

----

## Installation
```bash
$ npm i @frogebot/canvas
```
## Use
```js
let frogeCanvas = require("@frogebot/canvas")();
```

### Functions
The functions return a promise with an image buffer of the canvas
```js
// Draws text on a canvas with automatic wrapping
canvasText(text, fontSize, fontFamily, width, align = "center", lineSpacing = 1.5, fillStyle = "black", bg = "transparent", strokeStyle = "transparent", lineWidth = 0)
```

```js
// Draws a rectangle on a canvas
canvasRect(width, height, strokeStyle = "white", strokeWidth = 4, fillStyle = "black")
```

```js
// Draws a "window" on a canvas
canvasWindow(width, height, x, y, holeWidth, holeHeight, strokeStyle = "white", strokeWidth = 4, strokeOffset = 0, fillStyle = "black")
```