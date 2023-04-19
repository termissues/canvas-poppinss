## Usage

```js
const Canvas = require('canvas');
const { registerFont } = require('canvas');

const canvas = Canvas.createCanvas(690, 690);
const context = canvas.getContext('2d');
registerFont(require("@canvas-poppins/regular"), { family: "Poppins Regular" });
context.drawImage(background, 0, 0, canvas.width, canvas.height);
context.font = `18px "Poppins Regular"`;
context.fillStyle = '#ffffff';
```

## Packages

- `@canvas-poppins/regular` ([source](https://www.npmjs.com/package/@canvas-poppins/regular))
