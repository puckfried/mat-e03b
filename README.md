# Overview of HTML and CSS Commands

Here you will find a continuous overview of the HTML elements and CSS properties we have learned so far. This overview will be supplemented with new values in the coming days.
<br><br>

## Overview
1. [HTML Elements](#html-elements)
   - [Basic Structure](#0-basic-structure-of-an-html-page)
   - [Head Elements](#1-head-elements-not-visible-on-the-page-but-information-for-the-browser-and-google)
   - [Body Elements](#2-body-elements-the-visible-area-of-your-website)
       - [Block Elements](#21-block-elements-occupy-the-entire-width-of-the-screen)
       - [Inline Elements](#22-inline-elements-only-occupy-the-width-of-their-content)
2. [CSS Properties](#css-properties)
   - [Text Formatting](#text-formatting)
3. [Useful Keyboard Shortcuts](#useful-keyboard-shortcuts-windows)

<br><br><br>

## HTML Elements

**HTML** stands for ***Hypertext Markup Language*** and is a markup language used to structure and label the content of a webpage. HTML allows various elements such as headings, paragraphs, images, and links to be defined. These elements can then be styled with CSS to create an attractive website. <br>
So far, we have learned the following elements:

### 0. Basic Structure of an HTML Page

| HTML Element      | Description                                      | Example                            |
|:-----------------:|:------------------------------------------------:|:----------------------------------:|
| `<!DOCTYPE html>` | Defines the document type and HTML version       | `<!DOCTYPE html>`                  |
| `<html>`          | Root element of an HTML page                     | `<html>...</html>`                 |
| `<head>`          | Contains metadata and links to stylesheets, etc. | `<head>...</head>`                 |
| `<body>`          | Contains the visible content of the webpage      | `<body>...</body>`                 |
<br>

***Example***
```
<!DOCTYPE html>
<html>
    <head>...</head>
    <body>...</body>
</html>
```

<br>

### 1. Head Elements (not visible on the page, but information for the browser and Google)

| HTML Element | Description                                         | Example                                   |
|:------------:|:----------------------------------------------------:|:------------------------------------------:|
| `<title>`    | Title of the website, appears in the browser tab bar | `<title>My Website</title>`                |
| `<meta>`     | Meta information, e.g., character set or keywords   | `<meta charset="UTF-8">`                   |
| `<link>`     | Link to external files, e.g., CSS stylesheets       | `<link rel="stylesheet" href="style.css">` |


### 2. Body Elements (the visible area of your website)
    
#### 2.1 Block Elements (occupy the entire width of their parent element)

| HTML Element   | Description                             | Example                             |
|:--------------:|:---------------------------------------:|:-----------------------------------:|
| `<h1>`...`<h6>`| Headings                               | `<h1>Heading</h1>`                  |
| `<p>`          | Paragraph                              | `<p>Paragraph</p>`                  |
| `<ul>`         | Unordered list                         | `<ul><li>Element</li></ul>`         |
| `<ol>`         | Ordered list                           | `<ol><li>First Element</li></ol>`   |
| `<li>`         | List item                              | `<li>List item</li>`                |
| `<div>`        | Container element                      | `<div>Content</div>`                |


   
#### 2.2 Inline Elements (only occupy the width of their content)

| HTML Element | Description                          | Example                                  |
|:------------:|:-------------------------------------:|:----------------------------------------:|
| `<a>`        | Hyperlink (internal, external)        | `<a href="url">Link text</a>`            |
| `<br>`       | Special empty element for line breaks | `This is a text<br>new line`             |
| `<img>`      | Insert image                         | `<img src="url" alt="Image description">`|

<br><br><br>
## CSS Properties
**CSS** stands for ***Cascading Style Sheets*** and is used to define the appearance of HTML elements on a webpage. CSS allows various properties such as color, font, and positioning to be defined. By separating content and design, changing the appearance of the website becomes easier as only the CSS needs to be changed without editing the HTML code.


### Text Formatting
| Property          | Description                                  | Example                        |
|-------------------|----------------------------------------------|--------------------------------|
| `color`           | Sets the text color.                         | `color: blue;`                 |
| `font-size`       | Determines the font size.                    | `font-size: 16px;`             |
| `text-decoration` | Adds decorations like underlines.            | `text-decoration: underline;`  |
| `font-weight`     | Defines the thickness of the font.           | `font-weight: bold;`           |
| `font-family`     | Determines the font family.                  | `font-family: Arial, sans-serif;`|
| `font-style`      | Sets the style of the font (e.g., italic).   | `font-style: italic;`          |

<br><br><br>
## Useful Keyboard Shortcuts (Windows)

It's helpful to learn some keyboard shortcuts for common actions. With the keyboard, you can work faster and make fewer mistakes than using the mouse (touchpad). You might be a bit slower at the beginning, but in the long run, learning pays off.


### General Keyboard Shortcuts

Shortcuts that work in **VS Code** and other programs:

- Switch windows --> `Alt` + `Tab`
- Copy            --> `Ctrl` + `c`
- Cut             --> `Ctrl` + `x`
- Paste           --> `Ctrl` + `v`
- Search          --> `Ctrl` + `f`
- Save            --> `Ctrl` + `s`
- Select all      --> `Ctrl` + `a`


### VS Code

These handy combinations work only in VS Code:
- `Alt` + `Arrow Key` --> Move lines up/down
- `Alt` + `z`          --> Toggle word wrap on/off
- `Ctrl`+ `#`          --> Create a comment 
- `Ctrl`+ `l`          --> Highlight line


#### Emmet Abbreviations in VS Code

Emmet are shortcuts that VS Code converts into code, here are some brief examples for ***HTML***:
- `!`               --> creates a boilerplate code (basic structure)
- `lorem50`         --> creates a Lorem text with 50 words
- `div.box`         --> creates a `<div class="box">`
- `ul>li*3`         --> creates a `<ul>` with 3 `<li>` elements
- `a{read more}`    --> creates an `<a href="">read more</a>`
- `section>img+p+a` --> creates a section containing an `<img>`, `<p>`, and an `<a>`

You can combine these elements with each other to build very extensive code blocks. But use them only when you are confident with your HTML. The longer your combinations, the easier it is to produce errors and lose track. There are also Emmet abbreviations for CSS. A (very) comprehensive overview of the different possibilities can be found here:
***[Emmet Cheat Sheet](https://docs.emmet.io/cheat-sheet/)***
