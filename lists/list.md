# HTML Lists

HTML provides three types of lists: unordered lists, ordered lists, and definition lists.

## Unordered Lists (`unordered-list`)

Unordered lists are created using the `<ul>` (unordered list) element. Each item in the list is defined using the `<li>` (list item) element. The items are typically displayed with bullet points by default,
although the appearance can be customized using CSS.

Example:
```html
<ul>
  <li>Item 1</li>
  <li>Item 2</li>
  <li>Item 3</li>
</ul>
```
This will render as:

Item 1
Item 2
Item 3

## Ordered Lists (ordered-list)
The <ol> tag defines an ordered list. An ordered list can be numerical or alphabetical. The <li> tag is used to define each list item. Tip: Use CSS to style lists. Tip: For unordered list, use the <ul> tag.
```
<!DOCTYPE html>
<html>
<head>
    <title>Ordered List Example</title>
</head>
<body>
    <h1>Ordered List Example</h1>
    
    <ol>
        <li>Item 1</li>
        <li>Item 2</li>
        <li>Item 3</li>
        <li>Item 4</li>
    </ol>

</body>
</html>
```
