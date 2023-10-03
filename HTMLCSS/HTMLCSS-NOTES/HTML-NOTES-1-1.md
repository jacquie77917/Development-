### Legend element

he `legend` element acts as a caption for the content in the `fieldset` element. It gives users context about what they should enter into that part of the form.

```html
<legend></legend>
```

### Footer element

The `<footer>` tag defines a footer for a document or section.

A `<footer>` element typically contains:

- authorship information
- copyright information
- contact information
- sitemap
- back to top links
- related documents

You can have several `<footer>` elements in one document.

```html
<footer></footer>
```

### Body and Head element

Notice that everything you've added to the page so far is inside the `body` element. All page content elements that should be rendered to the page go inside the `body` element. However, other important information goes inside the `head` element.

### Title element

The `title` element determines what browsers show in the title bar or tab for the page.

```html
<title></title>
```

### HTML element

Notice that the entire contents of the page are nested within an `html` element. All other elements must be descendants of this `html` element.Add the `lang` attribute with the value `en` to the opening `html` tag to specify that the language of the page is English.

```html
<html lang="en">
```

### <DOCTYPE html>

All pages should begin with `<!DOCTYPE html>`. This special string is known as a declaration and ensures the browser tries to meet industry-wide specifications.

### Meta element

You can set browser behavior by adding self-closing `meta` elements in the `head`.Tell the browser to parse the markup into multiple languages by creating a `meta` element as a child of the `head` element. Set its `charset` attribute to `UTF-8`.

```html
<meta charset="UTF-8">

```
