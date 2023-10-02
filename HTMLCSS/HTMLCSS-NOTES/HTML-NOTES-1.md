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

You can add an attribute to assign what type of button this is .

```html
<botton type=""> Sign up </button>
```

### Input Tag

The input tag is a self-closing tag.。After the input tag, you need to specify the text type. So adding the "type" attribute inside the input tag is necessary. And the value of the type can be a range of options. like "text" . The "placeholder" attribute can be added after the "type attribute " to indicate what people have to input in the text box. 

In order for a form's data to be accessed by the location specified in the `action` attribute, you must give the text field a `name` attribute and assign it a value to represent the data being submitted. For example, you could use the following syntax for an email address text field: `<input type="text" name="email">`.

To prevent a user from submitting your form when required information is missing, you need to add the `required` attribute to an `input` element. There's no need to set a value to the `required` attribute. Instead, just add the word `required` to the `input` element, making sure there is space between it and other attributes.

You can use radio buttons for questions where you want only one answer out of multiple options.

```hmtl
<input type="text" required name="catphotourl" placeholder="Enter your username">
<input type="password" placeholder="Enter your password">
<input type="date">
<input type="time">
<input type="color">
<input type="file">  
<input type="radio"> Indoor 
```

### Input attributes

#### id

The `id` attribute is used to identify specific HTML elements. Each `id` attribute's value must be unique from all other `id` values for the entire page.

```html
<input id="">
```

#### name

Notice that both radio buttons can be selected at the same time. To make it so selecting one radio button automatically deselects the other, both buttons must have a `name` attribute with the same value.

```html
<input id="" name="">
```

#### value

If you select the `Indoor` radio button and submit the form, the form data for the button is based on its `name` and `value` attributes. Since your radio buttons do not have a `value` attribute, the form data will include `indoor-outdoor=on`, which is not useful when you have multiple buttons.

Add a `value` attribute to both radio buttons. For convenience, set the button's `value` attribute to the same value as its `id` attribute.

*Like radio buttons, form data for selected checkboxes are `name` / `value` attribute pairs. While the `value` attribute is optional, it's best practice to include it with any checkboxes or radio buttons on the page.

```html
<input id="" value="" name="">
```

#### checkbox

Forms commonly use checkboxes for questions that may have more than one answer. For example, here's a checkbox with the option of `tacos`: `<input type="checkbox"> tacos`.

```html
<input type="checkbox">
```

#### check

In order to make a checkbox checked or radio button selected by default, you need to add the `checked` attribute to it. There's no need to set a value to the `checked` attribute. Instead, just add the word `checked` to the `input` element, making sure there is space between it and other attributes.

```html
<label><input id="indoor" type="radio"checked name="indoor-outdoor" value="indoor"> Indoor</label>
```

### Lable element

`label` elements are used to help associate the text for an `input` element with the `input` element itself (especially for assistive technologies like screen readers). For example, `<label><input type="radio"> cat</label>` makes it so clicking the word `cat` also selects the corresponding radio button.

```html
<label><input type="radio"> cat</label>
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
