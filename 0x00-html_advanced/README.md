# 0x00. Advanced HTML


## Guidelines for HTML

When working with HTML, it's important to follow these guidelines:

- Use valid HTML syntax and adhere to standards defined by the W3C.
- Utilize semantic HTML to enhance accessibility and SEO.
- Keep your HTML code clean, well-organized, and properly indented.
- Use comments to document your code and clarify its purpose.

## Creating the Skeleton of an HTML5 Page

To create the basic structure of an HTML5 page, use the following template:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Page Title</title>
</head>
<body>
    <!-- Content goes here -->
</body>
</html>
```

This includes the necessary doctype declaration, HTML element, head section with metadata, and body section for content.

## Using Semantic HTML Tags

Semantic HTML tags provide meaning to the content structure. Some important semantic tags include:

- `<header>`, `<main>`, `<footer>`: For defining header, main content, and footer sections.
- `<article>`, `<section>`, `<aside>`: For structuring articles, sections, and side content.
- `<nav>`: For defining navigation menus.

Using semantic tags improves accessibility and helps search engines understand the content better.

## Use Cases of `<div>` vs `<span>`

- `<div>`: Used for grouping and structuring block-level content.
- `<span>`: Used for styling inline elements or small text sections.

Choose `<div>` for larger content blocks and `<span>` for smaller inline elements.

## Importance of Headings and Hierarchical Order

Headings (`<h1>` to `<h6>`) are important for organizing content hierarchically and improving document structure. Follow a logical order (from `<h1>` for main headings to `<h6>` for sub-subheadings) for better accessibility and SEO.

## Creating Lists in HTML

Use `<ul>` for unordered lists and `<ol>` for ordered lists. List items are defined with `<li>`.

```html
<ul>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ul>
```

## Differences Between Media Types (SVG, GIF, PNG, JPG)

- SVG: Scalable Vector Graphics for resolution-independent graphics.
- GIF: Graphics Interchange Format for animated images.
- PNG: Portable Network Graphics for lossless compression of images.
- JPG: Joint Photographic Experts Group for lossy compression of images.

Choose the appropriate format based on the image characteristics and use case.

## Structuring Data in a Table

Use `<table>`, `<tr>`, `<th>`, and `<td>` to create tables for organizing tabular data.

## Integrating Video and Audio in a Webpage

Use the `<video>` and `<audio>` elements to embed video and audio content.

```html
<video controls>
    <source src="video.mp4" type="video/mp4">
    Your browser does not support the video tag.
</video>

<audio controls>
    <source src="audio.mp3" type="audio/mpeg">
    Your browser does not support the audio tag.
</audio>
```

## Embedding External Content

Use `<iframe>` to embed external content like maps, videos, or other webpages.

```html
<iframe src="https://www.example.com" width="600" height="400" title="Embedded Content"></iframe>
```

## Correctly Structuring an HTML Page

Follow these guidelines to structure an HTML page effectively:

- Use doctype declaration (`<!DOCTYPE html>`).
- Define language and character set (`<html lang="en">`, `<meta charset="UTF-8">`).
- Include metadata (`<meta name="viewport" content="width=device-width, initial-scale=1.0">`).
- Title the page (`<title>Page Title</title>`).
- Organize content within `<head>` and `<body>` sections appropriately.

By following these guidelines and techniques, you can create well-structured and semantically meaningful HTML documents for your web projects. Happy coding! 🚀