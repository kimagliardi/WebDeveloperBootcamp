# HTML basics

In this unit, we will learn the **HTML** basics like:
- Write simple **HTML** documents;
- Understand the difference between closing and self closing tags;
- Write tags with attributes;
- Use **MDN** as a reference;
- Given an image, write the corresponding HTML.
----

## The general rule
```html
<tagName> Some content</tagName>


```


## Note about MDN

We will use a lot!

[Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Learn/HTML/Introduction_to_HTML)


## HTML Boilerplate and comments
 Every HTML document we create will start with this boilerplate:
[HTML Reference (MDN)](https://developer.mozilla.org/pt-BR/docs/Web/HTML/ReferenciaHTML)

 ```html
 <!DOCTYPE html>
<html>
<head>
<!-- metadata goes in head -->
    <title>Page Title</title>
</head>
<body>
<!--content goes in thebody -->
</body>
</html>
 ```

## Common Tags

```html
<h1>I'm a header </h1>
<h2>I'm a slightly smaller header </h2>
<h6>I'm the smallest header </h6>
<p>I'm a paragraph</p>
<button>I'm a button!</button>
<ul>
<li>List Item 1</li>
<li>List Item 2</li>
</ul>
<ol>
<li>List Item 1</li>
<li>List Item 2</li>
</ol>
```

## MDN Element reference

```html
Closing Tags
<h1>I need a closing tag </h1>
<p>Me too!</p>
Self-Closing Tags
<!-- No closing tag or inner text needed -->
<img src="corgi.png">
<link href="style.css">
<!-- Don't worry about what these tags do yet -->

```

---

## HTML Lists

```html
Ordered lists
<ol>
    <li>red</li>
    <li>orange</li>
    <li>green</li>
</ol>

Unordered lists
<!-- Will use bulletpoints -->
<ul>
    <li>red</li>
    <li>orange</li>
    <li>green</li>
</ul>

```

## Divs and Spans

The HTML Content Division element (< div >) is the generic container for flow content. It has no effect on the content or layout until styled using CSS.

Span is a inline container.

---

## Html Attributes


### MDN Attribute reference
```html
<tag name="value"></tag>

Images
<img src="corgi.png">

Links
<a href="www.google.com">Click me to go to Google</a>
<a href="www.reddit.com">Click me to go to Reddit</a>
```