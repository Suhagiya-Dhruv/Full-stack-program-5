# Input and Table Elements in HTML

## Input Elements

HTML provides a variety of input types to gather different kinds of user data. Here's a brief overview of the input elements used in your form:

### Text Input

```html
<input type="text" placeholder="Enter name" name="name" value="Rohan" required />
```

- `type="text"`: Standard single-line text input.
- `placeholder`: Displays a hint to the user of what to enter.
- `name`: Identifies the input.
- `value`: Pre-fills the input with the specified value.
- `required`: Ensures the user must fill out the field before submitting the form.

### Password Input

```html
<input type="password" placeholder="Enter password" />
```

- `type="password"`: Text input that masks the characters.

### Email Input

```html
<input type="email" placeholder="Enter Email" />
```

- `type="email"`: Validates the input to be in email format.

### Other Input Types

- `type="color"`: Provides a color picker.
- `type="number"`: Only allows numeric input.
- `type="date"`: Allows date selection.
- `type="time"`: Allows time selection.
- `type="datetime-local"`: Allows date and time selection.
- `type="month"`: Allows month and year selection.
- `type="checkbox"`: Allows multiple selections.
- `type="radio"`: Allows single selection from a group.
- `type="range"`: Provides a slider control.
- `type="tel"`: Validates input as a telephone number.
- `type="file"`: Allows file uploads.
- `type="hidden"`: Hides the input field from the user.
- `type="search"`: Provides a search input.
- `type="week"`: Allows week and year selection.
- `type="reset"`: Resets all form inputs to their default values.
- `type="submit"`: Submits the form data.
- `type="button"`: Creates a clickable button.
- `type="url"`: Validates input as a URL.
- `type="image"`: Submits the form with an image as the button.

### Textarea

```html
<textarea placeholder="Enter message"></textarea>
```

- Multi-line text input.

### Image

```html
<img src="https://img.freepik.com/free-photo/fresh-yellow-daisy-single-flower-close-up-beauty-generated-by-ai_188544-15543.jpg" alt="tree image" width="100%" height="100%">
```

- `src`: URL of the image.
- `alt`: Alternative text for the image.
- `width` and `height`: Dimensions of the image.

## Table Elements

Tables are used to display data in a tabular format. Below are the main elements used:

### Basic Table

```html
<table border="1" cellspacing="1" cellpadding="1">
    <tr>
        <th>Roll No.</th>
        <th>Name</th>
        <th>Mobile</th>
    </tr>
    <tr>
        <td>1</td>
        <td>Rohan</td>
        <td>87878787878</td>
    </tr>
    <tr>
        <td>2</td>
        <td>Manoj</td>
        <td>87878787878</td>
    </tr>
</table>
```

- `<table>`: Defines the table.
- `border`: Adds a border around the table and cells.
- `cellspacing`: Space between table cells.
- `cellpadding`: Space inside the table cells.
- `<tr>`: Table row.
- `<th>`: Table header cell.
- `<td>`: Table data cell.

### Advanced Table with Rowspan and Colspan

```html
<table border="1" cellspacing="1" cellpadding="1">
    <tr>
        <td>Row 1 Column 1</td>
        <td>Row 1 Column 2</td>
        <td>Row 1 Column 3</td>
    </tr>
    <tr>
        <td rowspan="2">Row 2 Column 1</td>
        <td>Row 2 Column 2</td>
        <td>Row 2 Column 3</td>
    </tr>
    <tr>
        <td>Row 3 Column 2</td>
        <td>Row 3 Column 3</td>
    </tr>
    <tr>
        <td colspan="3">Row 4 Column 1</td>
    </tr>
</table>
```

- `rowspan`: Merges cells vertically.
- `colspan`: Merges cells horizontally.