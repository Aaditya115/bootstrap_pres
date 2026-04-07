# Bootstrap Quick Reference

## Bootstrap in one sentence
Bootstrap is a front-end framework that helps you build responsive pages faster using a grid system, prebuilt components, and utility classes.

## Grid basics

```html
<div class="container">
  <div class="row">
    <div class="col-12 col-md-8">Main</div>
    <div class="col-12 col-md-4">Sidebar</div>
  </div>
</div>
```

- `container`: centered content wrapper
- `row`: horizontal layout row
- `col-*`: responsive column widths

## Breakpoints
- `sm`: 576px+
- `md`: 768px+
- `lg`: 992px+
- `xl`: 1200px+
- `xxl`: 1400px+

## Common classes
- Buttons: `btn btn-primary`
- Cards: `card`
- Alerts: `alert alert-warning`
- Navbar: `navbar`
- Forms: `form-control`

## Utility classes
- Margin: `m-2`, `mt-4`, `mb-3`
- Padding: `p-3`, `px-4`, `py-5`
- Text: `text-center`, `text-primary`, `fw-bold`
- Color: `bg-primary`, `bg-light`, `text-white`
- Flexbox: `d-flex`, `justify-content-between`, `align-items-center`
- Display: `d-none`, `d-md-block`
- Extras: `rounded`, `shadow-sm`

## Best uses
- Student projects
- Prototypes and MVPs
- Dashboards
- Form-heavy responsive pages

## Watch out for
- Default styles can feel generic
- Too many utility classes can clutter HTML
- Highly custom designs may need more custom CSS

## Memory tip
Bootstrap = `grid + components + utilities`
