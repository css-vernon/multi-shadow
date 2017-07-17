# shadow-size
It's an purpose of spec, that creates multiple shadows in an element that extends the current purpose of box-shadow

The purpose is create an shadow, that fit with the left or the right side of the screen. 
Actually box-shadow just allow us to duplicate the element, not adjust the size of it's shadow

```css
.element {
  --shadow-size: <width> <height>;
}
```
An shadow that starts from right to left, with `--shadow-size: 50vh auto; will get the half part of screen for this shadow.


# Reference
https://codepen.io/soutomario/pen/akwVZZ
