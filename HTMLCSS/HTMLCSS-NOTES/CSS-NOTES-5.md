### CSS Inheritance

In CSS, **inheritance** controls what happens when no value is specified for a property on an element.

CSS properties can be categorized in two types:

- **inherited properties**, which by default are set to the [computed value](https://developer.mozilla.org/en-US/docs/Web/CSS/computed_value) of the parent element
- **non-inherited properties**, which by default are set to [initial value](https://developer.mozilla.org/en-US/docs/Web/CSS/initial_value) of the property

Refer to [any CSS property](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#index) definition to see whether a specific property inherits by default ("Inherited: yes") or not ("Inherited: no").

#### CSS Inherited properties

1. `azimuth`
2. `border-collapse`
3. `border-spacing`
4. `caption-side`
5. `color`
6. `cursor`
7. `direction`
8. `elevation`
9. `empty-cells`
10. `font-family`
11. `font-size`
12. `font-style`
13. `font-variant`
14. `font-weight`
15. `font`
16. `letter-spacing`
17. `line-height`
18. `list-style-image`
19. `list-style-position`
20. `list-style-type`
21. `list-style`
22. `orphans`
23. `pitch-range`
24. `pitch`
25. `quotes`
26. `richness`
27. `speak-header`
28. `speak-numeral`
29. `speak-punctuation`
30. `speak`
31. `speech-rate`
32. `stress`
33. `text-align`
34. `text-indent`
35. `text-transform`
36. `visibility`
37. `voice-family`
38. `volume`
39. `white-space`
40. `widows`
41. `word-spacing`

### Shorthands for margin and padding

For margin property, when there are 4 different values from all sides, to use the shorthand property, the order goes clockwise(top-right-bottom-left)

```css
.card{
    margin: 10px 20px 30 px 40px;
}
```

However, if the top and bottom (verticle)has the same value while the right and left (horizontal)have the same value, you can mark it as the following

```css
margin: 10px auto 
```
