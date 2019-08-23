# gsap-babylonjs-plugin
Based on GSAP PIXI Plugin https://github.com/noprotocol/gsap-pixi-plugin

```
// js
import 'gsap-babylon-plugin'

TweenLite.to(mesh, 1, {
  babylon: {
    alpha: 0,
    color: '#fffff00'

    x: 10, // translate
    y: 10,
    z: 10,

    rotation: 90, // rotate X,Y,Z in deg
    rotationX: 10,
    rotationY: 10,
    rotationZ: 10,

    scale: 0,
    scaleX: 10,
    scaleY: 10,
    scaleZ: 10,
  },

  ease: Expo.easeOut,
  onComplete: () => {},
  ... blah blah
})
```


