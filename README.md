## centered

CSS Brick For Centering

## Install

```bash
$ npm install centered
```

## Usage

Mix your Brick with it to have it centered:

```js
var Brick = require('brick')
var Centered = require('centered')

module.exports = Brick(Centered);
```

And add `centered` class to any DOM element that you'd like to center:

```html
<div class="content centered">
  centered!
</div>
```
