### An Id Selector

You can use the `id` selector to target a specific `div` element. An id selector is defined by a name with a hash symbol directly in front of it, like this:

The `#*id*` selector styles the element with the specified id.

```css
#firstname {
  width: 250px;
}
```

### Max-width

The max-width property in CSS is **used to define the maximum width of an element**. The value of the width cannot be larger than the value by max-width. If the content is larger than the max-width then it will go to the next line and if the content is smaller than the max-width then it has no effect

```css
max-width: 500px;
```

### Fallback value

In CSS, fallbacks are **used to ensure that the design and layout of a website or application are still usable and readable even if some CSS properties are not supported by a browser**. For example, if a browser does not support a certain font or color, a fallback font or color can be used instead.

```css
    h1,h2{font-family: Impact, serif;}
```

### Pseudo-classes:

A pseudo-class is used to define a special state of an element.

For example, it can be used to:

- Style an element when a user mouses over it
- Style visited and unvisited links differently
- Style an element when it gets focus

```css
selector:pseudo-class {
  property: value;
}
/* unvisited link */
a:link {
  color: #FF0000;
}

/* visited link */
a:visited {
  color: #00FF00;
}

/* mouse over link */
a:hover {
  color: #FF00FF;
}

/* selected link */
a:active {
  color: #0000FF;
}
```

### Opacity

 With the value `0`, or 0%, the element will be completely transparent, and at `1.0`, or 100%, the element will be completely opaque like it is by default.

```css
.sleeve {
  width: 110px;
  height: 25px;
  background-color: white;
  opacity: 0.5;
}
```

### Alpha Channel

To add an alpha channel to an `rgb` color, use the `rgba` function instead.

The `rgba` function works just like the `rgb` function, but takes one more number from `0` to `1.0` for the alpha channel:

```css
.sleeve {
  width: 110px;
  height: 25px;
  background-color: rgba(255, 255, 255, 0.5)
}
```
