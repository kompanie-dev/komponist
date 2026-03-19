# Komponist 🎹

Komponist is a compact dependency-free CSS framework for styling standard HTML elements.
It also includes components for creating alerts, badges, loading spinners and tabs.

You can check out a demo of all styled elements and features using the [GitHub Pages demo](https://kompanie-dev.github.io/komponist/demo/).

## Components

The following components are supported:

```html
<!-- Alerts -->
<div class="alert">Lorem ipsum dolor sit amet...</div>
<div class="alert success">Lorem ipsum dolor sit amet...</div>

<!-- Badges -->
<span class="badge">Default</span>
<span class="badge error">Error</span>

<!-- Spinner -->
<div style="height: 100px; width: 100px">
    <div class="spinner"></div>
</div>

<!-- Tabs -->
<div class="tabs">
    <button class="tab active">Tab 1</button>
    <button class="tab">Tab 2</button>
    <button class="tab">Tab 3</button>
</div>
```
Keep in mind that Komponist is a pure CSS library.
Therefore the tabs are styled, but if you want proper tab switching, you need to write your own JavaScript code for that.

## Elements

Komponist contains styles for the following elements:

* `<a>`
* `<blockquote>`
* `<body>`
* `<button>`
* `<details> + <summary>`
* `<dialog>`
* `<div>`
* `<h1> - <h6>`
* `<hr>`
* `<img>`
* `<input>`
    * `checkbox`
    * `color`
    * `date`
    * `email`
    * `file`
    * `number`
    * `password`
    * `radio`
    * `range`
    * `tel`
    * `text`
    * `url`
* `<label>`
* `<nav>`
* `<progress>`
* `<select> (+ <option>)`
* `<span>`
* `<table> (+ <td>, <th>)`
* `<textarea>`

To use the styling in your project just apply the correct CSS class (`.a`, `.body`, `.button`, `.details`, `.div`, `.h1`-`.h6`, `.input`, `.label`, `.nav`, `.progress`, `.select`, `.span`, `.textarea`) to the element.

You can take a look at `demo/index.html` to see how elements get styled.
You need to supply CSS variables (themes) for the framework to function properly.
There is a default dark and light theme in `themes/default`.
You can enforce a dark theme by only importing `dark.css`, a light theme by using `light.css` and auto-switching, based on the [users browser preference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference/At-rules/@media/prefers-color-scheme) using `auto.css`.

## Usage

At first you need to install the package using the following command:

```
npm i @kompanie/komponist
```

After the installation you can include the CSS in your app.

## Getting Started

Execute `npm install` and then use `npm start` to run the demo project.

The site will be available at [localhost:8000](http://localhost:8000).

To create a bundle of the library you can use `npm run build`.

To create a minified bundle of the library use `npm run build-minified`.