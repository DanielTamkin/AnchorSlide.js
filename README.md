# AnchorSlide.js

a simple jQuery plugin to animate anchor tags.

a very simplistic demo can be found [here](http://danieltamkin.github.io/AnchorSlide.js/)

`$("#your-element").AnchorSlide();`
### Settings
speed(in Milliseconds):

```
$("#your-element").AnchorSlide({
  speed: 100
});
```
target:

```
$("#your-element").AnchorSlide({
  target: a.only-some-a-tags
});
```

_can be combined_
```
$("#your-element").AnchorSlide({
  speed: 100,
  target: a.only-some-a-tags
});
```
