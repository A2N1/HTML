# HTML Cheat Sheet – COMPLETE LEARNING VERSION 📘 (HTML5)

This cheat sheet covers **core HTML concepts**, elements, attributes, forms, media, and modern HTML5 features.  
Suitable for beginners and refreshers (Frontend / Web Development).

---

## Table of Contents

- [HTML Cheat Sheet – COMPLETE LEARNING VERSION 📘 (HTML5)](#html-cheat-sheet--complete-learning-version--html5)
  - [Table of Contents](#table-of-contents)
  - [1. Basics](#1-basics)
  - [2. Document Structure](#2-document-structure)
  - [3. Text Elements](#3-text-elements)
  - [4. Links](#4-links)
  - [5. Images](#5-images)
  - [6. Lists](#6-lists)
  - [7. Tables](#7-tables)
  - [8. Forms](#8-forms)
  - [9. Input Types](#9-input-types)
  - [10. Buttons \& Controls](#10-buttons--controls)
  - [11. Media](#11-media)
  - [12. Semantic Elements](#12-semantic-elements)
  - [13. Metadata \& SEO](#13-metadata--seo)
  - [14. HTML5 Features](#14-html5-features)
  - [15. Global Attributes](#15-global-attributes)
  - [16. Best Practices](#16-best-practices)
  - [End](#end)

---

## 1. Basics

~~~html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My Page</title>
</head>
<body>
    <h1>Hello World</h1>
    <p>This is a paragraph.</p>
</body>
</html>
~~~

---

## 2. Document Structure

~~~html
<html>           <!-- Root element -->
<head>           <!-- Metadata, scripts, styles -->
<title>Page</title>
</head>
<body>           <!-- Content visible to user -->
</body>
</html>
~~~

---

## 3. Text Elements

~~~html
<h1>Main Heading</h1>
<h2>Subheading</h2>
<p>This is a paragraph.</p>
<strong>Bold text</strong>
<em>Italic text</em>
<small>Small text</small>
<mark>Highlighted</mark>
~~~

---

## 4. Links

~~~html
<a href="https://example.com">Visit Example</a>
<a href="#section1">Jump to Section</a>
<a href="mailto:test@example.com">Send Email</a>
~~~

---

## 5. Images

~~~html
<img src="image.jpg" alt="Description" width="300" height="200">
~~~

---

## 6. Lists

~~~html
<!-- Ordered list -->
<ol>
    <li>First</li>
    <li>Second</li>
</ol>

<!-- Unordered list -->
<ul>
    <li>Item A</li>
    <li>Item B</li>
</ul>
~~~

---

## 7. Tables

~~~html
<table>
    <thead>
        <tr>
            <th>Name</th>
            <th>Age</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Max</td>
            <td>30</td>
        </tr>
    </tbody>
</table>
~~~

---

## 8. Forms

~~~html
<form action="/submit" method="post">
    <label for="name">Name:</label>
    <input type="text" id="name" name="name">
    <input type="submit" value="Submit">
</form>
~~~

---

## 9. Input Types

~~~html
<input type="text">
<input type="password">
<input type="email">
<input type="number">
<input type="date">
<input type="checkbox">
<input type="radio">
<input type="file">
<input type="range">
<input type="color">
~~~

---

## 10. Buttons & Controls

~~~html
<button>Click Me</button>
<input type="submit" value="Submit">
<input type="reset" value="Reset">
~~~

---

## 11. Media

~~~html
<!-- Audio -->
<audio controls>
    <source src="audio.mp3" type="audio/mpeg">
    Your browser does not support audio.
</audio>

<!-- Video -->
<video width="400" controls>
    <source src="video.mp4" type="video/mp4">
    Your browser does not support video.
</video>
~~~

---

## 12. Semantic Elements

~~~html
<header>Header content</header>
<nav>Navigation links</nav>
<main>Main content</main>
<article>Article content</article>
<section>Section content</section>
<aside>Sidebar content</aside>
<footer>Footer content</footer>
~~~

---

## 13. Metadata & SEO

~~~html
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="Page description for SEO">
<meta name="author" content="Max">
<link rel="stylesheet" href="styles.css">
<script src="script.js"></script>
~~~

---

## 14. HTML5 Features

~~~html
<canvas id="myCanvas" width="400" height="200"></canvas>
<video autoplay muted loop>
    <source src="video.mp4" type="video/mp4">
</video>
<audio autoplay loop>
    <source src="audio.mp3" type="audio/mpeg">
</audio>
<progress value="70" max="100"></progress>
<meter value="0.6">60%</meter>
~~~

---

## 15. Global Attributes

~~~html
<div id="main" class="container" style="color:red" title="Tooltip"></div>
~~~

---

## 16. Best Practices

- Always declare `<!DOCTYPE html>`
- Use semantic tags for accessibility
- Include `alt` for images
- Keep code readable & properly indented
- Validate HTML for errors
- Use relative paths wisely
- Separate content (HTML), style (CSS), and behavior (JS)

---

## End
