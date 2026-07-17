# Day 8 - Styling the Resume with CSS

## Objective

The objective of today's session was to style an HTML resume using CSS. Styling improves the appearance, readability, and user experience of a webpage.

---

# What is CSS?

CSS (Cascading Style Sheets) is used to control the design and layout of HTML pages. It allows developers to change colors, fonts, spacing, alignment, and overall appearance without changing the HTML structure.

---

# Why Use CSS?

- Makes websites visually attractive.
- Separates design from content.
- Improves readability.
- Makes pages responsive.
- Allows code reuse.

---

# Ways to Add CSS

## 1. Inline CSS

```html
<h1 style="color: blue;">Resume</h1>
```

---

## 2. Internal CSS

```html
<style>
h1{
    color: blue;
}
</style>
```

---

## 3. External CSS

```html
<link rel="stylesheet" href="style.css">
```

---

# Styling a Resume

Common properties used while styling a resume:

## Background Color

```css
body{
    background-color:#f5f5f5;
}
```

---

## Font Family

```css
body{
    font-family: Arial, sans-serif;
}
```

---

## Text Color

```css
h1{
    color:#333;
}
```

---

## Padding

```css
section{
    padding:20px;
}
```

---

## Margin

```css
section{
    margin-bottom:20px;
}
```

---

## Border

```css
img{
    border:2px solid black;
}
```

---

## Border Radius

```css
img{
    border-radius:50%;
}
```

---

## Box Shadow

```css
.container{
    box-shadow:0 0 10px rgba(0,0,0,0.2);
}
```

---

# Layout Techniques

For styling a resume, the following CSS concepts are useful:

- Flexbox
- Grid
- Box Model
- Margin
- Padding
- Width
- Height

---

# Best Practices

- Use external CSS files.
- Keep consistent spacing.
- Use readable fonts.
- Maintain a clean color scheme.
- Avoid unnecessary styles.
- Organize CSS into sections.

---

# Learning Outcome

Today I learned how CSS improves the appearance of a webpage. I understood how to style an HTML resume using colors, fonts, spacing, borders, shadows, and layout techniques like Flexbox and Grid. A well-designed resume is easier to read and gives a professional impression.
