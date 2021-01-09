# Responsive Grid Framework

## Description

This repository is a responsive 12-column grid layout built as a final CSS exercies from The Odin Project.

## The Basics

### Container

The grid container is defined by "grid":

```html
<div class="grid">
</div>
```

## Columns

Columns are defined by "column-1" to "column-12":

```html
<div class="grid">
  <div class="column-12">
    <h1>Hello World</h1>
  </div>
</div>
```

## Breakpoints

Predefined breakpoints are included for a responsive design.
The breakpoints are inspired by Bootstrap:<br>
Large: min 992px, Medium: 768px-992px, Small: max 768px.

These breakpoints can be defined with the columns:

```html
<div class="grid">
  <div class="column-6 column-md-12 column-sm-12">
    <h1>Hello World</h1>
    <h1>Hello World</h1>
  </div>
</div>
```

## Extras

### Typography

All typography is defined by "font-".

Two font-family's are available, sans and sans-serif:<br>

  "font-serif": "Times New Roman", Times, serif<br>
  "font-sans": sans-serif, Verdana 

Font-weight:<br>
  "font-bold": 700<br>
  "font-thin": 200

### Colour

Background-color is defined as "bg-"<br>
Text color is defined as "text-"

Color shades available:<br>
  dark: `4a4a4a`<br>
  muted: `rgba(74, 74, 74, 0.7)`<br>
  light: `eee`<br>
  white: `fff`

  ## References

  [The Odin Project](https://www.theodinproject.com/courses/html-and-css/lessons/design-your-own-grid-based-framework)

  [Demo](https://andrewbonas.github.io/odin_clone/)






