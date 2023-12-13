### Pattern Attribute

With `type="password"` you can use the `pattern` attribute to define a regular expression that the password must match to be considered valid.

Add a `pattern` attribute to the password `input` element to require the input match: `[a-z0-5]{8,}`

The above is a regular expression which matches eight or more lowercase letters or the digits `0` to `5`.

```html
<label for="new-password">Create a New Password: <input id="new-password" type="password" pattern="[a-z0-5]{8,}" required /></label>
```

### Select Element

The `<select>` element is used to create a drop-down list.

The `<select>` element is most often used in a form, to collect user input.

The `name` attribute is needed to reference the form data after the form is submitted (if you omit the `name` attribute, no data from the drop-down list will be submitted).

The `id` attribute is needed to associate the drop-down list with a label.

The [<option>](https://www.w3schools.com/tags/tag_option.asp) tags inside the `<select>` element define the available options in the drop-down list.

**Tip:** Always add the [<label>](https://www.w3schools.com/tags/tag_label.asp) tag for best accessibility practices!

```html
<label for="cars">Choose a car:</label>

<select name="cars" id="cars">
  <option value="volvo">Volvo</option>
  <option value="saab">Saab</option>
  <option value="mercedes">Mercedes</option>
  <option value="audi">Audi</option>
</select>
```

### Textarea Element

The `<textarea>` tag defines a multi-line text input control.

The `<textarea>` element is often used in a form, to collect user inputs like comments or reviews.

A text area can hold an unlimited number of characters, and the text renders in a fixed-width font (usually Courier).

The size of a text area is specified by the `cols` and `rows` attributes (or with CSS).

The `name` attribute is needed to reference the form data after the form is submitted (if you omit the `name` attribute, no data from the text area will be submitted).

The `id` attribute is needed to associate the text area with a label. 

**Tip:** Always add the [<label>](https://www.w3schools.com/tags/tag_label.asp) tag for best accessibility practices!

```html
<label for="w3review">Review of W3Schools:</label>

<textarea id="w3review" name="w3review" rows="4" cols="50">
At w3schools.com you will learn how to make a website. They offer free tutorials in all web development technologies.
</textarea>
```

### Utility tag

Utilities are **simple HTML classes typically scoped to a single CSS property, like border-style or background-color** . Utilities can be used additively to style an object from scratch or to override a style defined in component CSS.
