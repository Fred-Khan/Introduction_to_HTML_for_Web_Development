# Introduction to HTML for Web Development

- **Subtitle**: First Class: Building a Web Form
- **Author**: Fred Khan
- **Date**: August 2025

## Agenda
- What is HTML and its role in web development
- Setting up Notepad and VS Code with Live Server
- HTML basics: tags, semantic structure, forms, tables
- Brief introduction to ARIA for accessibility
- Hands-on: Build a personal details form

## What is HTML?
- HTML = HyperText Markup Language
- Defines the structure and content of web pages
- Uses *tags* to create elements (e.g., headings, forms)
- HTML5: Latest version with semantic and multimedia support
- **Visual**: HTML renders as structured content, e.g., a form with labeled inputs in a browser.

## Getting Started with Notepad
1. Open Notepad on your Windows 10 laptop
2. Create a file named `index.html`
3. Write and save the code below
4. Open in a browser to see "Hello, World!"

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My First Page</title>
</head>
<body>
  <h1>Hello, World!</h1>
  <p>This is my first web page.</p>
</body>
</html>
```

## Installing VS Code and Live Server
1. Download Visual Studio Code: [https://code.visualstudio.com](https://code.visualstudio.com)
2. Install the *Live Server* extension
3. Open `index.html` in VS Code
4. Right-click and select "Open with Live Server" for live previews
- **Visual**: Live Server refreshes the browser automatically when you save changes.

## HTML Structure
- **Key Components**:
```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>My Page</title>
</head>
<body>
  <h1>Welcome</h1>
</body>
</html>
```
- `<!DOCTYPE html>`: Declares HTML5
- `<html lang="en">`: Root element with language
- `<head>`: Metadata (title, charset)
- `<body>`: Visible content

## Common HTML Tags
- Headings: `<h1>` to `<h6>`
- Paragraphs: `<p>`
- Links: `<a href="...">`
- Images: `<img src="..." alt="...">`
- Lists: `<ul>`, `<ol>`, `<li>`
- **Example**:
```html
<h1>My Page</h1>
<p>Welcome to my site!</p>
<ul>
  <li><a href="https://example.com">Visit Example</a></li>
  <li><img src="https://via.placeholder.com/150" alt="Placeholder"></li>
</ul>
```

## Semantic HTML
- Tags that describe meaning, not just appearance
- Examples: `<header>`, `<main>`, `<footer>`, `<section>`
- Improves accessibility and SEO
- **Example**:
```html
<header>
  <h1>My Site</h1>
</header>
<main>
  <section>
    <p>Content here</p>
  </section>
</main>
<footer>
  <p>Copyright 2025</p>
</footer>
```

## HTML Forms
- `<form>`: Container for input fields
- `<label>`: Associates text with inputs
- `<input>`: Text, date, or other input types
- `<select>`: Dropdown menus
- `<button>`: Submit or reset actions
- **Example**:
```html
<form>
  <label for="name">Name:</label>
  <input type="text" id="name" name="name">
  <button type="submit">Submit</button>
</form>
```

## HTML Tables
- `<table>`: Container for tabular data
- `<tr>`: Table row
- `<th>`: Table header
- `<td>`: Table data
- **Example**:
```html
<table>
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Alice</td>
    <td>25</td>
  </tr>
</table>
```

## ARIA for Accessibility
- ARIA = Accessible Rich Internet Applications
- Adds attributes to enhance accessibility (e.g., for screen readers)
- Example: Use `role="form"` and `aria-label` for forms
- **Example**:
```html
<form id="my-form" role="form" aria-label="User details">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name">
</form>
```

## Hands-On: Personal Details Form
- **Task**:
  - Create `form.html` with:
    - Fields: Title (dropdown: Mr, Ms, Dr), First Name, Last Name, Date of Birth, Street Number, Street Name, Suburb, Postcode
    - Buttons: Submit and Cancel
    - Use `<form>`, `<fieldset>`, `<label>`, semantic tags, and ARIA
- **Steps**:
  1. Start in Notepad, then switch to VS Code
  2. Use Live Server to preview
  3. Save as `form.html`

## Explore More
- Visit W3Schools ([https://www.w3schools.com/html/](https://www.w3schools.com/html/)) for HTML5 elements
- Focus on forms (`<textarea>`, `<radio>`) and tables (`colspan`)
- **Homework**:
  - Add an email field to `form.html`
  - Create `experiment.html` with a table or list (e.g., favorite books)

## Wrap-Up
- You learned: HTML basics, forms, tables, semantic tags, ARIA
- You built: A personal details form
- Next week: CSS to style your form
