### Viewpoint Height

The vh unit in CSS measure the “viewport height”. The viewport is **the area of the browser in which a website is displayed**. The vh unit allows you to easily measure the height of the viewport and size elements in relation to this visible area.

```css
body {
  width: 100%;
  height: 100vh;
}
```

### Viewport Width

The full form of VW is **viewport width**. It works like the percentage unit. Specifying 10vw is equivalent to occupying 10% of entire visible screen width

```css
form{
  margin: 0 auto;
  max-width: 500px;
  min-width: 300px;
  width: 60vw;

}
```

### REM unit

In CSS rem stands for “root em”, a unit of measurement that represents the font size of the root element. This means that `1rem` equals the font size of the `html` element, which for most browsers has a default value of 16px. Using rem can help ensure consistency of font size and spacing throughout your UI.

According to the [W3C spec](https://www.w3.org/TR/2013/CR-css3-values-20130730/#font-relative-lengths) the definition for one rem unit is:

> Equal to the computed value of `font-size` on the root element. When specified on the `font-size` property of the root element, the rem units refer to the property’s initial value.

#### REM VS. EM

[https://ww[SitePoint](https://www.sitepoint.com/understanding-and-using-rem-units-in-css/)w.sitepoint.com/understanding-and-using-rem-units-in-css/](https://ww%5BSitePoint%5D(https://www.sitepoint.com/understanding-and-using-rem-units-in-css/)w.sitepoint.com/understanding-and-using-rem-units-in-css/)

### :last-of-type

The **`:last-of-type`** [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) [pseudo-class](https://developer.mozilla.org/en-US/docs/Web/CSS/Pseudo-classes) represents the last element of its type among a group of sibling elements.

##### For example: Styling the last paragraph

```html
<h2>Heading</h2>
<p>Paragraph 1</p>
<p>Paragraph 2</p>
```

```css
p:last-of-type {
  color: red;
  font-style: italic;
}
```

### CSS [attribute] Selector

he `[attribute]` selector is used to select elements with a specified attribute.

```css
a[target] {
  background-color: yellow;
} 
```

### CSS  justify-content Property

The `justify-content` property aligns the flexible container's items when the items do not use all available space on the main-axis (horizontally).

**Tip:** Use the `[align-items](https://www.w3schools.com/cssref/css3_pr_align-items.php)` property to align the items vertically.

**Note:** The `justify-content` property can also be used on a grid container to align grid items in the inline direction. For pages in English, inline direction is left to right and block direction is downward.

[CSS justify-content property](https://www.w3schools.com/cssref/css3_pr_justify-content.php)

```css
justify-content: flex-start|flex-end|center|space-between|space-around|space-evenly|initial|inherit;
```
