# HTML Notes

*HTML* is the standard markup language for Web pages

## Basic Tags

### Headings Tags

The highest you can go with headings will bt h6

```html
<h1> Hello World </h1>
<h2> I am a cat </h2>
<h3> I am a black cat </h3>
<h4>...</h4>
<h5>...</h5>
<h6>...</h6>###
```

### Paragraph Tag

```html
<p> Please don't ever tell me that you don't love cats!
I would end you!
</p> 
```

### Image Tag

Image tag is a self-closing tag. To render the img, you have to add src=""

If you want the image to scale with the browser, you can add the attribute width="100%" inside the img tag.

```html
<img src=""> 
```html
<img src="" width="100%"> 
```

## Nesting Tags

### Div Tag

<div></div> tag is like a container. It envelops the html tags like its children. However, it doesn't change th layout of the page. It isi invisible but it will improve the readibility for any coders. Like you can div an article and style it with CSS. Div can nest multipe div tags under it and become an "HTMl document tree".

```html
<div>
    <h1></h1>
    <h2></h2>
   <div> <p></p></div>
    <img src:"">

</div>
```

## Interactive Tags

### Button Tag

```html
<botton> Sign up</button>
```



### Input Tag

After the input tag, you need to specify the text type.

```bash
type="date" type="time" type="color"
```
