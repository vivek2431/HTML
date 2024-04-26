# HTML Forms

HTML forms are an essential part of web development, allowing users to input data that can be sent to a server for processing. Below is an overview of the key components of an HTML form.

## Form Element (`<form>`)

The `<form>` element creates an HTML form for user input and acts as a container for various input elements like text fields, checkboxes, radio buttons, and submit buttons.

### Example Form

```html
<form>
  <label for="fname">First name:</label><br>
  <input type="text" id="fname" name="fname"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname">
</form>
```
This form collects the user’s first name and last name.

## Input Types (`<input>`)
The `<input>` element is versatile and can be displayed in different ways based on the type attribute.
Example of Radio Buttons
```<p>Choose your favorite Web language:</p>
<form>
  <input type="radio" id="html" name="fav_language" value="HTML">
  <label for="html">HTML</label><br>
  <input type="radio" id="css" name="fav_language" value="CSS">
  <label for="css">CSS</label><br>
  <input type="radio" id="javascript" name="fav_language" value="JavaScript">
  <label for="javascript">JavaScript</label>
</form>
```
Users can select their preferred language.

## Label Element (`<label>`)
The `<label>` tag defines a label for form elements, improving accessibility and usability.
Example Label
```<label for="fname">First name:</label>
<input type="text" id="fname" name="fname">
```
The label “First name” is associated with the input field.
