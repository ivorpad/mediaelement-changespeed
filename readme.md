## MediaElementJS: Change Speed

Simplified the speed plugin to handle speed changes on click instead of a menu.

![](https://user-images.githubusercontent.com/52452/60034563-3c7e6080-96ab-11e9-81bd-582adc4d7462.gif)

### Usage

```html
<script src="/path/to/mediaelement-and-player.js"></script>
<script src="/path/to/speedchange.js"></script>
```

```javascript
const player = new MediaElementPlayer(
  document.querySelector("audio"), 
{
  defaultSpeed: '1.00',
  speeds: ['1.25','1.50', '2.00'],
  features: [
    [...],
    "changespeed"
  ]
});
```
