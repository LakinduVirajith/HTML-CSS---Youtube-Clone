<div style="display: grid; grid-template-columns: 2fr 1fr; column-gap: 16px; margin-bottom: 16px;">
    <h1>HTML-CSS---Youtube-Clone</h1>
    <div style="display: flex; gap: 24px; justify-content: end">
        <a href="https://www.w3.org/html/">
        <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/html5/html5-original-wordmark.svg" alt="HTML5 Logo" height="55" style="margin-right: 10px;" />
        </a>
        <!-- CSS LOGO -->
        <a href="https://www.w3schools.com/css/">
            <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original-wordmark.svg" alt="CSS3 Logo" height="55" />
        </a>
    </div>
</div>

---

# USES OF HTML <!-- USES OF HTML -->

## Tags, Element and Attributes

HTML tags are used to hold the HTML element. HTML element holds the content. HTML attributes are used to describe the characteristic of an HTML element in detail.

## Block Level Element

A block-level element always starts on a new line, and the browsers automatically add some space (a margin) before and after the element.

Ex: `<p>, <h1>, <h2>, <h3>, <h4>, <h5>, <h6>, <ul>, <ol>, <dl>, <pre>, <hr />, <blockquote> and <address>`

## Inline Elements

Inline elements display in a line. They do not force the text after them to a new line.

Ex: `<span>, <a>, <code>, <strong>, <img />, <cite>, <button>, <input />, <textarea>, <select>, <small>`

# USES OF CSS <!-- USES OF CSS -->

## CSS Property

A CSS property is an attribute that defines how an HTML element should be styled. CSS properties control various aspects of an element's appearance, such as its size, color, font, spacing, and more.

## CSS Selectors

## Simple selectors: select elements based on name, id, class

```
<p>This is a paragraph element.</p>
<p id="unique-paragraph">This paragraph has a unique ID.</p>
<p class="important">This paragraph has an important class.</p>
```

```
p {
    color: blue;
}
#unique-paragraph {
    font-weight: bold;
}
.important {
    font-size: 18px;
}
```

## Combinator selectors: select elements based on a specific relationship between them

```
<div class="container">
  <p>This is a paragraph inside a container.</p>
</div>
```

```
.container p {
    background-color: lightgray;
}
```

## Pseudo-class selectors: select elements based on a certain state

```
<div class="container">
    <a href="#" class="link">Click me</a>
<div class="container">
<div></div>
```

```
a.link:hover {
    text-decoration: underline;
}
```

## Pseudo-elements selectors: select and style a part of an element

```
<p>This is a <span>highlighted</span> text.</p>
```

```
p span::first-letter {
    font-size: 24px;
    font-weight: bold;
}
```

## Attribute selectors: select elements based on an attribute or attribute value

```
<input type="text" class="username" required>
<a href="https://example.com" target="_blank">Visit Example</a>
```

```
input[type="text"] {
    border: 1px solid #ccc;
}
a[href^="https://"] {
    color: blue;
}
```

## Object Fit

The object-fit property is used to specify how an `<img>` or `<video>` should be resized to fit its container

Ex: `object-fit: contain, cover, fill;`

## Object Position

The object-position property of CSS specifies how an image or video element is positioned with x/y coordinates inside its content box.

Ex: `object-position: bottom, left, right, top, center, inherit, initial;`

## Display

The display property specifies the display behavior (the type of rendering box) of an element.

Ex: `display: inline, block, inline-block, flex, grid, table;`

## Initial and Inherit

initial - sets the property to its default value, as defined by the browser.

inherit - It is used to inherit the property from it’s parents’ elements.

## Vertical Align

vertical-align defines the vertical alignment for the content of a table cell or for an inline element against the rest of the inline flow.

Ex: `vertical-align: top, bottom, middle, baseline;`

## Font Fallback

Font fallback in the font-family property refers to specifying a list of fonts to be used as alternatives if the user's system does not have the first-choice font installed.

Ex: `font-family: 'Roboto', 'Open Sans', Helvetica, Arial, sans-serif;`

## Semantic Tags

A semantic tag is like a special marker in HTML that makes content more meaningful. It tells browsers and developers what type of content it holds, making web pages easier to read and improving accessibility and help the search engines and other user devices to determine the importance and context of web pages.

Ex: `<h1>, <h2>, <h3>, <h4>, <h5>, <h6>, <p>, <ul>, <ol>, <li>, <table>, <caption>, <img>`

## Semantic Element

In web development, a semantic element is like a labeled container that gives meaning to content. It helps browsers and search engines understand the structure and importance of the information on a webpage.

Ex: `<header>, <nav>, <main>, <article>, <section>, <aside>, <footer>`

# USEFUL CSS PROPERTIES <!-- USEFUL CSS PROPERTIES -->

#### vertical-align: top;

#### object-fit: contain;

#### object-position: top;

#### box-shadow: inset 5px 5px 10px rgba(0, 0, 0, 0.15);

#### transition: box-shadow 0.15s, opacity 0.15s;

#### display: inline-block;

#### display: grid;

#### grid-template-columns: 100px 100px 1fr;

#### column-gap: 20px;

#### row-gap: 20px;

#### flex-direction: row;

#### flex: 1;

#### flex-shrink: 0;

#### border-bottom: 1px solid rgb(228, 228, 228);

#### pointer-events: none;

#### white-space: nowrap;
