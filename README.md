# wat-beckett-beans
HTML Example for WAT

## Overview
This repository contains HTML examples demonstrating fundamental web development concepts and HTML element usage.

## HTML Tag Types

### 1. Block-Level Elements
Block-level elements start on a new line and take up the full width available.

**Common block-level elements:**
- `<div>` - Generic container for flow content
- `<p>` - Paragraph
- `<h1>` to `<h6>` - Headings (levels 1-6)
- `<ul>`, `<ol>`, `<li>` - Unordered lists, ordered lists, and list items
- `<header>`, `<footer>`, `<nav>`, `<section>`, `<article>`, `<aside>` - Semantic HTML5 elements
- `<form>` - User input form
- `<table>`, `<tr>`, `<td>`, `<th>` - Table elements
- `<blockquote>` - Block quotation
- `<pre>` - Preformatted text
- `<hr>` - Horizontal rule (thematic break)

### 2. Inline Elements
Inline elements do not start on a new line and only take up as much width as necessary.

**Common inline elements:**
- `<span>` - Generic inline container
- `<a>` - Hyperlink
- `<img>` - Image
- `<strong>`, `<b>` - Bold text (strong emphasis / stylistic bold)
- `<em>`, `<i>` - Italic text (emphasis / stylistic italic)
- `<code>` - Inline code
- `<small>` - Smaller text
- `<mark>` - Highlighted text
- `<sub>`, `<sup>` - Subscript and superscript
- `<abbr>` - Abbreviation
- `<cite>` - Citation

### 3. Self-Closing (Void) Elements
Elements that do not have closing tags and cannot contain content.

**Common self-closing elements:**
- `<img>` - Image
- `<br>` - Line break
- `<hr>` - Horizontal rule
- `<input>` - Input field
- `<meta>` - Metadata
- `<link>` - External resource link
- `<area>` - Image map area
- `<col>` - Table column
- `<embed>` - Embedded content
- `<source>` - Media source
- `<track>` - Text track for media
- `<wbr>` - Line break opportunity

### 4. Semantic Elements
HTML5 introduced semantic elements that describe their meaning to both browser and developer.

**Important semantic elements:**
- `<header>` - Introductory content or navigational links
- `<nav>` - Navigation links
- `<main>` - Main content of document
- `<section>` - Thematic grouping of content
- `<article>` - Self-contained composition
- `<aside>` - Content tangentially related to content around it
- `<footer>` - Footer of document or section
- `<figure>`, `<figcaption>` - Self-contained content with optional caption
- `<time>` - Time or date
- `<mark>` - Highlighted/marked text

## Useful HTML Facts

### Document Structure
- Every HTML document should start with `<!DOCTYPE html>` to declare HTML5
- The `<html>` element is the root element
- The `<head>` contains metadata not visible to users
- The `<body>` contains visible page content

### Attributes
- **Global attributes** work on any element: `id`, `class`, `style`, `title`, `lang`, `data-*`
- **Boolean attributes** don't need values: `disabled`, `checked`, `selected`, `required`
- Attributes should be lowercase in HTML5
- Attribute values should be quoted (preferably with double quotes)

### Accessibility
- Always include `alt` attributes on images for screen readers
- Use semantic HTML instead of generic `<div>` and `<span>` when possible
- Ensure proper heading hierarchy (`<h1>` → `<h2>` → `<h3>`, etc.)
- Use `<label>` elements with form inputs
- Include ARIA attributes when semantic HTML isn't sufficient

### Best Practices
- **Indentation**: Use consistent indentation (2 or 4 spaces)
- **Case**: Use lowercase for element names and attributes
- **Closing tags**: Always close non-void elements
- **Nesting**: Properly nest elements (don't overlap tags)
- **Semantics**: Choose elements based on meaning, not appearance
- **Validation**: Validate HTML using W3C validator
- **Comments**: Use `<!-- comment -->` to document complex sections

### Character Entities
Special characters that need to be escaped in HTML:
- `&lt;` for <
- `&gt;` for >
- `&amp;` for &
- `&quot;` for "
- `&apos;` for '
- `&nbsp;` for non-breaking space
- `&copy;` for ©
- `&reg;` for ®

### HTML5 Features
- **Canvas**: `<canvas>` for drawing graphics
- **SVG**: Scalable Vector Graphics support
- **Video/Audio**: Native `<video>` and `<audio>` elements
- **Form validation**: Built-in form validation attributes
- **Local storage**: localStorage and sessionStorage APIs
- **Geolocation**: Navigator.geolocation API
- **Drag and Drop**: Native drag and drop support

### Common Mistakes to Avoid
- Missing `<!DOCTYPE html>` declaration
- Not closing tags properly
- Using deprecated elements (`<font>`, `<center>`, `<marquee>`)
- Inline styles instead of CSS
- Missing `alt` text on images
- Incorrect heading hierarchy
- Not using semantic elements
- Missing or incorrect `lang` attribute on `<html>`

## File Structure
```
contact.html  - Contact page
index.html    - Home page
menu.html     - Menu page
images/       - Image assets
```

## Resources
- [MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [W3C HTML Specification](https://www.w3.org/TR/html/)
- [HTML Validator](https://validator.w3.org/)
- [Can I Use](https://caniuse.com/) - Browser compatibility tables

## License
See LICENSE file for details.
