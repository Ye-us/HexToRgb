```js
    const rgb = [57, 107, 77]; // cor rgb
    const hex = `#${(((rgb[0] << 16) | (rgb[1] << 8) | rgb[2]) >>> 0)
      .toString(16)
      .padStart(6, "0")}`;
    console.log(hex); // return #396b4d
```
