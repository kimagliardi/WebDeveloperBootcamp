# Introduction to CSS

- Objectives:
    - Define CSS and the role that it plays in WebDev;
    - View websites before and after CSS has been added;
    - Understand the "general rule" for CSS syntax.

### The general rule
```css
selector{
    property: value;
    anotherProperty: value;
}
```
Example

```css
h1{
    color: blue;
    font-size: 56px;
}

img{
    border-color: red;
    border-width: 3px;
}
```

Using **RGB** colors

[WebSite with colors name and RGB value..](http://colours.neilorangepeel.com)

Hexadecimal

\# + String of hexadecimal numbers (from 0-F)

We also can use RGBA..

---

## Background and border


```css
body{
    background: #95a5a6;
}
div{
    background: #3498db;
}
p{
    color: #ecf0f1;
}
```


---
## Selectors basics Todo list
The basics: Element, ID and Class
- Element selector: This type of selector selects the element based on the element name.

- ID Selector: This selector is used for selecting a HTML element based on the id value.

- Class selector: For class selectors we specify the CSS like this. It is similar to the id selector but the syntax is different. It styles the elements of specified class.


**See todolist.html and todos.css**

Select all elements with a given class

```html
<div>
    <p class="highlight">You say yes</p>
    <p>I say no</p>
</div>

<div>
    <p class="highlight">You say goodbye</p>
    <p>I say hello</p>
</div>
```

```css
div{
    background: purple;
}

.highlight{
    background: yellow;
}
``` 


More advanced selectors

[Selectors list](https://code.tutsplus.com/tutorials/the-30-css-selectors-you-must-memorize--net-16048)

- Element;
- Class;
- ID;
- Start;
- Descendant selector;
- Adjacent selector;
- Attribute selector;
- 

---


## Specifity and the cascade
