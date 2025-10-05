# CSS Advanced Project

This project demonstrates advanced CSS concepts and layout techniques for building modern, responsive web pages.

## What is CSS?

CSS (Cascading Style Sheets) is a language used to describe the presentation and design of HTML documents. It controls the layout, colors, fonts, and overall visual appearance of web pages.

## How to Add Style to an Element

You can add styles to HTML elements in three ways:
- **Inline:** Using the `style` attribute directly on an element.
- **Internal:** Placing `<style>` tags within the `<head>` of your HTML.
- **External:** Linking a separate `.css` file using `<link rel="stylesheet" href="style.css">`.

## What is a Class?

A class is a reusable CSS selector that lets you apply the same styles to multiple elements. Define a class in CSS with a dot (`.`), e.g., `.my-class { color: red; }`, and use it in HTML as `<div class="my-class"></div>`.

## What is a Selector?

A selector targets HTML elements to apply styles. Examples:
- `p` selects all `<p>` tags.
- `.className` selects all elements with that class.
- `#idName` selects the element with that ID.

## How to Compute CSS Specificity Value

CSS specificity determines which rule applies when multiple rules target the same element. Specificity is calculated as:
- Inline styles: 1000
- IDs: 100
- Classes/attributes/pseudo-classes: 10
- Elements/pseudo-elements: 1

Add up the values for each selector; the highest wins.

## What are Box Properties in CSS?

Every element is a box with properties:
- `width` and `height`
- `padding` (space inside the box)
- `border` (edge of the box)
- `margin` (space outside the box)

This is known as the [box model](https://developer.mozilla.org/en-US/docs/Learn/CSS/Building_blocks/The_box_model).

## How Does the Browser Load a Webpage?

1. The browser requests the HTML file from the server.
2. It parses the HTML and requests linked resources (CSS, images, JS).
3. CSS is parsed and applied to the HTML structure.
4. The browser builds the DOM (Document Object Model) and CSSOM (CSS Object Model).
5. The page is rendered visually for the user.

---