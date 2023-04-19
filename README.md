@canvas-poppins/regular
====

## Usage

```js
const { registerFont, createCanvas } = require('canvas');
registerFont(require("@canvas-poppins/regular"), { family: "Poppins Regular" });
const canvas = createCanvas(400, 48);
const ctx = canvas.getContext('2d');
ctx.font = `20px "Poppins Regular"`;
ctx.fillText("Poppins Regular", 5, 30);
const png = canvas.toBuffer();
```