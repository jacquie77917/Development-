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

### CSS Color Models

1.the additive RGB (red, green, blue) model used in electronic devices

2. the subtractive CMYK (cyan, magenta, yellow, black) model used in print.

In the additive RGB color model, primary colors are colors that, when combined, create pure white. But for this to happen, each color needs to be at its highest intensity.

First, in the CSS rules `.one`, `.two`, and `.three`, adjust the values in the `rgb` function so that the `background-color` of each element is set to pure black. Remember that the `rgb` function uses the additive color model, where colors start as black and change as the values of red, green, and blue increase.

```css
.container{ background-color:rgb(0, 0, 0);} 
```

#### Secondary colors

Secondary colors are the colors you get when you combine primary colors. You might have noticed some secondary colors in the last step as you changed the red, green, and blue values.

To create the first secondary color, yellow, update the `rgb` function in the `.one` CSS rule to combine pure red and pure green.

```css
.one {
  background-color: rgb(255, 255, 0);
}
```

#### Tertiary colors

To create the tertiary color orange, update the `rgb` function in the `.one` CSS rule so that red is at the max value, and set green to `127`.

```css
.one {
  background-color: rgb(255, 127, 0);
}
```

### CSS Function

A function is a piece of code that can take an input and perform a specific action. The CSS `rgb` function accepts values, or arguments, for red, green, and blue, and produces a color:

Each red, green, and blue value is a number from `0` to `255`. `0` means that there's 0% of that color, and is black. `255` means that there's 100% of that color.

```css
.one{rgb(255, 0, 0);}
```

### Hex Color Values

Hex color values start with a `#` character and take six characters from 0-9 and A-F. The first pair of characters represent red, the second pair represent green, and the third pair represent blue. For example, `#4B5320`.

```css
.green {background-color: #00FF00;}
```
