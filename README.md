# Komponist

Komponist is a dependency-free compact CSS framework for styling standard HTML elements.
It contains styles for the following elements:
* `<a>`
* `<button>`
* `<dialog>`
* `<h1> - <h6>`
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
* `<progress>`
* `<select> (+ <option>)`
* `<textarea>`

To use the styling in your project just apply the correct CSS class (`.a`, `.button`, `.h1`-`.h6`, `.input`, `.label`, `.progress`, `.select`, `.textarea`) to the element.
The library also resets `margin`, `padding`, `box-sizing` and font for all elements and applies a `background` and `color` to the `body` element.

You can take a look at demo/index.html to see how elements get styled.
You need to supply CSS variables for the framework to function.
There is a default dark and light theme in `source/_variables.css`.

## Usage

At first you need to install the package using the following command:
```
npm i @kompanie/komponist
```
After the installation you can include the CSS in your app.

## Getting Started

Execute `npm install` and then use `npm start` to run the demo project.

The site will be available at [localhost:8000](http://localhost:8000).

To create a minified build of the library you can use `npm run build`.