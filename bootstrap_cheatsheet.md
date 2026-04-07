# Bootstrap One-Page Cheat Sheet

## What Bootstrap is
Bootstrap is a front-end framework that helps developers build responsive websites faster using a grid system, prebuilt components, and utility classes.

## Core idea to remember
Bootstrap = `grid + components + utilities + responsive design`

## 1. Layout: container, row, column

```html
<div class="container">
  <div class="row">
    <div class="col-12 col-md-8">Main</div>
    <div class="col-12 col-md-4">Sidebar</div>
  </div>
</div>
```

- `container`: centered content wrapper
- `row`: horizontal group of columns
- `col-*`: column width
- `col-12`: full width on small screens
- `col-md-8`: 8 of 12 columns on medium screens and up

## 2. Breakpoints

- `sm`: `576px+`
- `md`: `768px+`
- `lg`: `992px+`
- `xl`: `1200px+`
- `xxl`: `1400px+`

Memory tip:
- mobile first means the smallest layout happens by default
- larger breakpoint classes change the layout as the screen gets wider

## 3. Useful components

- Buttons: `btn btn-primary`
- Cards: `card`
- Alerts: `alert alert-warning`
- Navbar: `navbar navbar-expand-lg`
- Forms: `form-control`
- JS components: modal, dropdown, collapse, offcanvas

Why they matter:
- less CSS to write
- faster prototypes
- more consistent pages

## 4. Utility classes you will use a lot

### Spacing
- Margin: `m-2`, `mt-4`, `mb-3`, `mx-auto`
- Padding: `p-3`, `px-4`, `py-2`

### Text and color
- `text-center`
- `text-primary`
- `text-white`
- `fw-bold`
- `bg-light`
- `bg-dark`

### Flex and display
- `d-flex`
- `justify-content-between`
- `align-items-center`
- `d-none`
- `d-md-block`

### Extras
- `rounded`
- `shadow-sm`
- `w-100`

## 5. Quick example

```html
<div class="card p-3 shadow-sm">
  <h2 class="text-primary">Bootstrap Card</h2>
  <p class="mb-3">Fast styling with classes.</p>
  <button class="btn btn-success">Save</button>
</div>
```

## 6. Bootstrap vs plain CSS and JavaScript

- Bootstrap is mainly for layout and styling
- Plain CSS means you build the styling system yourself
- JavaScript is a programming language for behavior and logic
- Bootstrap includes some JavaScript-powered UI parts, but Bootstrap is not JavaScript

## 7. How you usually start using Bootstrap

```html
<link
  href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css"
  rel="stylesheet"
>
```

- Add the Bootstrap CSS file
- Build your page with Bootstrap classes in normal HTML
- Add custom CSS when you want your own look
- Add Bootstrap JavaScript only for interactive components like modals or dropdowns

## 8. When Bootstrap is a good choice

- small projects
- dashboards
- prototypes and MVPs
- teams that want consistent UI patterns

## 9. When Bootstrap is not the best choice

- highly custom brand-heavy websites
- projects that need a unique design system
- teams that prefer utility-first styling like Tailwind

## 10. Best practices

- start with layout first
- use utilities for quick spacing and alignment
- do not memorize every class; learn the patterns
- customize Bootstrap with your own CSS when needed
