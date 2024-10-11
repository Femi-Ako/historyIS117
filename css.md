# CSS (Cascading Style Sheets)

## Overview
Cascading Style Sheets (CSS) is a stylesheet language used to control the presentation and layout of web pages. It allows web developers to separate content from design, making it easier to maintain and style websites.

## Who
- **Håkon Wium Lie**: A Norwegian web pioneer who proposed CSS in 1994 while working with the World Wide Web Consortium (W3C).
- **Bert Bos**: Collaborated with Lie on the development of CSS and played a key role in its evolution.

## What
CSS is used to define the visual appearance of web content, including:
- **Layout**: Control over the positioning and arrangement of elements on a page.
- **Styling**: Specifications for colors, fonts, margins, spacing, and more.
- **Responsive Design**: Techniques like media queries enable designs to adapt to different screen sizes and devices.

## Why
CSS is essential for web development for several reasons:
- **Separation of Concerns**: By separating content (HTML) from presentation (CSS), developers can create cleaner and more maintainable code.
- **Consistency**: CSS allows for consistent styling across multiple web pages, ensuring a unified look and feel.
- **Flexibility**: Developers can easily change the appearance of a website without altering the underlying HTML structure.

## When
- **1994**: Håkon Wium Lie introduces CSS as a way to improve web design.
- **1996**: CSS1 is officially released by the W3C, providing basic styling features.
- **1998**: CSS2 is published, introducing new capabilities such as absolute positioning and media types.
- **2011**: CSS3 is introduced, bringing significant enhancements like new selectors, properties, and the ability to create animations and transitions.

## How
CSS works by applying styles to HTML elements through a series of rules:
- **Selectors**: Identify the HTML elements to style (e.g., tags, classes, or IDs).
- **Properties and Values**: Define the specific style to apply (e.g., `color: blue;`, `font-size: 16px;`).
- **Cascading Order**: CSS follows a hierarchy that determines which styles are applied when conflicts arise, based on specificity and source order.

### Example
Here’s a simple CSS rule:

```css
h1 {
    color: blue;
    font-size: 24px;
    text-align: center;
}

