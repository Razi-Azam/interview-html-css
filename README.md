# HTML & CSS Interview Questions

## Topics

## HTML
- [Q1. What is HTML ? ](#what-is-html)
- [Q2. What is the difference between HTML elements and tags? ](#difference-between-HTML-elements-and-tags)

- [Q3. What is the difference between a block-level element and an inline element? ](#difference-between-a-block-level-element-and-an-inline-element)

- [Q4. How to create a nested webpage in HTML?](#create-a-nested-webpage-in-html)


- [Q5. What are the new HTML5 elements?](#new-html5-elements)

- [Q6. What is Cell Spacing and Cell Padding?](#cell-spacing-and-cell-padding)


---
## CSS
- - [Q1. ](#)



---

## What is HTML
[Topics](#topics)

- Stands for HyperText Markup Language.
- A standard text formatting language used in web development for creating web pages.
- Browser is its interpreter and HTML instructs the browser what and how to display.


## Difference between HTML elements and tags
[Topics](#topics)

| HTML elementa | HTML Tags |
| ------------- | --------- |
| These are the starting and ending parts of the HTML elements.  | These are the combinations of the starting tag, the content, and the ending tag. |
| Or these are the building blocks of an HTML element. | Or these are the building blocks of the HTML document. |
| For example, ``` <b>, <p>, </b> , </div>, <img> etc. ``` | For example, ``` <p> Hello </p> ``` |

### HTML Attribute: 
- It helps in defining the characteristics of the HTML elements. It is present only in the starting tag. The common attribute that is used for styling the element is “Style” attribute.
```html
<img src=”myImage.png” alt=”myImage” style=”width: 40px” />

Here, <img> is the tag.
src, alt, and style are the attributes.
The whole thing is an HTML image element.

```

## Difference between a block-level element and an inline element
[Topics](#topics)

| Block Level Element | Inline Element |
| -------- | -------- |
| Always starts on a new line. | It doesn’t and be in a line |
| It takes the full width. | It only takes the space as per its requirement. |
| For example, ``` <p> ,<div>, <address>, <article>, <canvas>, <h1>-<h6>, <hr>, <li>, <ol>, <ul>, <pre>, <video>, <table>, <form>, <fieldset>, <noscript>, etc.  ``` | For example, ``` <span>, <a>, <b>, <br>, <button>, <i>, <img>, <input>, <label>, <script>, <select>, <small>, <strong>, <sub>, <sup>, <textarea>, etc.  ``` |


## Create a nested webpage in HTML?
[Topics](#topics)

- The "iframe" and the "embed" tag help in displaying the nested webpage in two different ways.
- iframe: It defines an inline	frame (includes scroll bar and border) within the browser for displaying the other website.
```
<iframe src=”http://www.myWebsite.abc” height=”100px” width=”80px”> </iframe>
```

- embed: Mostly, it is used for including other videos or audios on website. It also can be used for nesting the website.
```
<embed src=”https://www.myWebsite.abc” type=”text/html” />
```

## New HTML5 Elements
[Topics](#topics)

- The following are the new HTML5 Elements.
```
<article>, <aside>, <header>, <footer>, <audio>, <video>, <datalist>, <details>, <embed>, <figure>, <hgroup>, <mark> For highlighting the text</mark>, <meter>,<nav>, <output>, <progress>, <time>
```
- The ```<canvas>``` tag is used to draw the graphics on the web page with the help of JavaScript. It does not have border and text.


## Cell Spacing and Cell Padding
[Topics](#topics)

- Cell spacing: Space between the cells. (Space outside the cell)
- Cell Padding: Space between the cell border and the content. (Space inside the cell)
For example,
```html
<table border=”2” cellspacing=”4” cellpadding=”6” > </table>
```