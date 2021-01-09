# Responsive Grid Framework

## Description

This repository is a responsive 12-column grid layout built as a final CSS exercies from The Odin Project

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
The breakpoints are inspired by Bootstrap:
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

### Typograrphy

All typography is defined by "font-"

Two font-family's are available, sans and sans-serif:
  "font-serif": "Times New Roman", Times, serif 
  "font-sans": sans-serif, Verdana 

Font-weight:
  "font-bold": 700
  "font-thin": 200

### Colour

Background-color is defined as "bg-"
Text color is defined as "text-"

Color shades available:
  dark: `4a4a4a`
  muted: `rgba(74, 74, 74, 0.7)`
  light: `eee`
  white: `fff`

  ## References

  [The Odin Project](https://www.theodinproject.com/courses/html-and-css/lessons/design-your-own-grid-based-framework)
  [Demo](https://andrewbonas.github.io/odin_clone/)






