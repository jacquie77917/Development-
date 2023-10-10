# CSS Basics

## CSS Syntax

You select an HTML tag (in this case, <body></body>to style (this is called a selector), color is the "Property" and red will be the "Value".

```css
Body {color: red;}
```

### Inline Element

The inline element will let images stack up next to each other(horizontally)

The block element will let images stack up on top of each other (vertically)

```css
display: inline;
display: block;
```

### Margin Element

This element is to ass space on top of the page

```css
margin-top: 20px; 
```

### Div Tag

controls the positioning of the elements it contains indirectly via the contatiner

```html
<div>
    <img sr="google.png">
    <input type="text">
<div>
```

### How Div works in CSS for margin

This is for a better sturcture just in case one html element is being revmoved or replaced  and led to the disappearnce of the margin 

```css
div {

    margin-top= 200px; 

}
```

### CSS Class for Div

There could be thousands of div tags under another div tag. To style them individually, you need to set " CSS Class". For example, you call the first <div> main, then you have to go back to the CSS sheet to change the style from div { margin-top= 200px; to .main= 200px;}

```html
<div class="main">
    <div>

    </div>
</div>
```

```css
.main{
    margin-top: 200px;
}
```

### Margins

Note that if you add margin top/bottom collapes with eacher other(collapsing margins). The margin with a larger pixel will be the dominent one. 

```css
div {
    margin-top:
    margin-left:
    margin-right:
    margin-bottom:
}
```

### Centering with Margins

```css
1.Display:block;
2.Must have a width
3.Margin left/right:auto
```
