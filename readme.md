# HTML Elements and Their Usage

This document explains the usage of various HTML elements demonstrated in the provided HTML code. HTML elements are the building blocks of a webpage, each serving a specific purpose to structure and display content effectively.

## Semantic vs Non-semantic Tags

Semantic tags clearly describe their meaning in a way that both the browser and the developer can understand. Non-semantic tags do not provide any information about their contents.

### Example:

```html
<!-- Non-semantic tag -->
<div>hello</div>

<!-- Semantic tag -->
<header>hello</header>
<article>Article tag</article>
<time>time tag</time>
```

- `<div>`: A generic container for flow content.
- `<header>`: Represents introductory content or a set of navigational links.
- `<article>`: Represents a self-contained composition in a document.
- `<time>`: Represents a specific period in time.

## Styling Tags

Styling tags help emphasize or differentiate parts of the text within the document.

### Example:

```html
<p>Lorem ipsum dolor sit amet <b>consectetur</b> adipisicing elit. Possimus saepe sunt <i>molestias</i> impedit ratione eum doloremque suscipit laborum <u>deleniti.</u> Animi eum <b><i>aperiam</i></b> tempora laborum maiores, cum, amet delectus aut cupiditate minima a, in sed perferendis officia quis libero nam consequatur. Voluptates atque asperiores dolorem! Doloribus consequatur aliquid voluptatum ipsa molestiae.</p>
```

- `<b>`: Makes the text bold.
- `<i>`: Italicizes the text.
- `<u>`: Underlines the text.

## Subscript and Superscript Tags

Subscript and superscript tags are used to specify text that should be displayed as subscript or superscript respectively.

### Example:

```html
<p>H<sub>2</sub>O</p>
<p>a<sup>2</sup>+b<sup>2</sup></p>
```

- `<sub>`: Defines subscript text.
- `<sup>`: Defines superscript text.

## List Tags

HTML provides various list elements to define different types of lists.

### Unordered List

An unordered list is a collection of items where the order does not matter.

```html
<ul type="square">
    <li>Item 1</li>
    <li>Item 1</li>
    <li>
        type of
        <ul>
            <li>item 1</li>
        </ul>
    </li>
    <li>Item 1</li>
</ul>
```

- `<ul>`: Defines an unordered list.
- `<li>`: Defines a list item.

### Ordered List

An ordered list is a collection of items where the order does matter.

```html
<ol type="i" start="5">
    <li>item 1</li>
    <li>item 1</li>
    <li>item 1</li>
    <li>item 1</li>
</ol>
```

- `<ol>`: Defines an ordered list.
- `<li>`: Defines a list item.

### Description List

A description list is used to display name/value pairs such as terms and definitions.

```html
<dl>
    <dt>Title</dt>
    <dd>Lorem ipsum dolor sit amet consectetur adipisicing elit. Hic molestiae explicabo ipsam sequi quos minus nihil accusantium quidem sapiente libero similique, possimus, recusandae neque quisquam ipsum, incidunt placeat iste ab.</dd>
    <dt>Title</dt>
    <dd>Lorem ipsum dolor sit amet consectetur adipisicing elit. Hic molestiae explicabo ipsam sequi quos minus nihil accusantium quidem sapiente libero similique, possimus, recusandae neque quisquam ipsum, incidunt placeat iste ab.</dd>
</dl>
```

- `<dl>`: Defines a description list.
- `<dt>`: Defines a term/name in a description list.
- `<dd>`: Describes each term/name.

## Button Tag

The `<button>` element defines a clickable button.

```html
<button>Click</button>
```

## Anchor Tag

The `<a>` element (or anchor) creates a hyperlink to other web pages, files, locations within the same page, email addresses, or any other URL.

### Example:

```html
<a href="https://www.nasdaq.com/market-activity/stocks/googl">google</a>
<br/>
<a href="https://google.com" target="_blank">google</a>
```

- `href`: Specifies the URL of the page the link goes to.
- `target="_blank"`: Opens the linked document in a new window or tab.

## Horizontal Rule

The `<hr>` tag defines a thematic break in an HTML page (e.g., a shift of topic).

```html
<hr/>
```

---

This document provides an introduction and explanation of various HTML elements used in the example code. Understanding these elements will help you build well-structured and semantically meaningful web pages. For further details, you can refer to the [HTML Reference](https://htmlreference.io/).