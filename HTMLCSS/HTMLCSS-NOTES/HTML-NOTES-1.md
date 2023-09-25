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

HTML attributes are special words used inside the opening tag of an element to control the element's behavior. The `src` attribute in an `img` element specifies the image's URL (where the image is located).

All `img` elements should have an `alt` attribute. The `alt` attribute's text is used for screen readers to improve accessibility and is displayed if the image fails to load. For example, `<img src="cat.jpg" alt="A cat">` has an `alt` attribute with the text `A cat`.

```html
<img src="" alt=""> 
```html
<img src="" width="100%"> 
```

### Anchor Tag

An anchor tag  is when you want to insert a hypter link. You can also nest an anchor tag inside another tag. The tagart="_blank" allows the link to be opened in a new tab. 

```html
<a> href:""Click here</a>
<p>Please click <a href:"google.com" tagart="_blank">here</a>.</p>
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

The input tag is a self-closing tag.。After the input tag, you need to specify the text type. So adding the "type" attribute inside the input tag is necessary. And the value of the type can be a range of options. like "text" . The "placeholder" attribute can be added after the "type attribute " to indicate what people have to input in the text box. 

```hmtl
<input type="text" placeholder="Enter your username">
<input type="password" placeholder="Enter your password">
<input type="date">
<input type="time">
<input type="color">
<input type="file">
```

### Document Structure

```html
<!doctype html> is not a tag. It's the metadata for the browser. 
This is to tell the browser that we are using HTML 5.
```

```html
<!doctype html>
<html>
    <head>
    Metadata(styles,title,scripts.etc.)
    </body>
    <body>
        The tage you see on the page
    </head>
</html>
```
