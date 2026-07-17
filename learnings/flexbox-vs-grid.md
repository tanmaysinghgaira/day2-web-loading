# Day 7 - Flexbox vs Grid

## What is Flexbox?

Flexbox (Flexible Box Layout) is a one-dimensional layout system in CSS. It is used to arrange items either in a row or in a column. It is best for aligning and distributing space between elements.

Example:

```css
.container {
  display: flex;
}
```

---

## Features of Flexbox

- One-dimensional layout
- Easy alignment of items
- Responsive design
- Control spacing between elements
- Supports horizontal and vertical alignment

---

## What is CSS Grid?

CSS Grid is a two-dimensional layout system. It allows developers to control both rows and columns at the same time, making it ideal for complex page layouts.

Example:

```css
.container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
}
```

---

## Features of Grid

- Two-dimensional layout
- Works with rows and columns
- Suitable for complete page layouts
- Easy placement of elements
- Highly responsive

---

## Flexbox vs Grid

| Flexbox | Grid |
|---------|------|
| One-dimensional | Two-dimensional |
| Works in rows or columns | Works in rows and columns together |
| Best for small layouts | Best for complete page layouts |
| Easy content alignment | Easy page structure creation |
| Simple navigation bars | Dashboards, galleries, full websites |

---

## When to Use Flexbox

- Navigation bars
- Buttons
- Cards
- Forms
- Menus
- Small UI components

---

## When to Use Grid

- Landing pages
- Dashboards
- Image galleries
- Blog layouts
- Portfolio websites
- Admin panels

---

## Example

### Flexbox

```css
.container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}
```

### Grid

```css
.container {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 20px;
}
```

---

## Advantages of Flexbox

- Simple to learn
- Excellent alignment
- Great for responsive components
- Less code for small layouts

---

## Advantages of Grid

- Powerful layout system
- Handles complex designs
- Easy row and column management
- Better control over page structure

---

## Summary

Flexbox and Grid are both modern CSS layout systems. Flexbox is best for arranging items in a single direction, while Grid is ideal for creating complete two-dimensional layouts with rows and columns. Using both together helps build clean, responsive, and professional websites.
