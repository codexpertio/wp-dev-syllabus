# Module 1: Frontend Fundamentals

## **Table of Contents**
- [HTML Basics](#html-basics)
- [CSS Essentials](#css-essentials)
- [Bootstrap](#bootstrap)
- [Tailwind CSS](#tailwind-css)

---

## **HTML Basics**
### Core Structure
```html
<!DOCTYPE html>
<html>
<head>
    <title>Page Title</title>
</head>
<body>
    <h1>Heading</h1>
    <p>Paragraph</p>
</body>
</html>
```

### Semantic Elements
- `<header>`, `<nav>`, `<main>`, `<section>`, `<article>`, `<footer>`.

---

## **CSS Essentials**
### Box Model
- **Margin**: Space outside element.
- **Border**: Edge of element.
- **Padding**: Space inside element.
- **Content**: Actual text/image.

### Flexbox
```css
.container {
    display: flex;
    justify-content: center;
    align-items: center;
    gap: 1rem;
}
```

### CSS Grid
```css
.grid-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-gap: 20px;
}
```

### Media Queries
```css
@media (max-width: 768px) {
    .container {
        flex-direction: column;
    }
}
```

---

## **Bootstrap**
### Grid System
```html
<div class="container">
    <div class="row">
        <div class="col-md-6">Left Column</div>
        <div class="col-md-6">Right Column</div>
    </div>
</div>
```

### Key Utilities
- Spacing: `.mt-3`, `.px-4`
- Text: `.text-center`, `.fw-bold`
- Flex: `.d-flex`, `.justify-content-between`

---

## **Tailwind CSS**
### Utility-First Example
```html
<div class="p-6 bg-gray-100 flex items-center justify-between">
    <h2 class="text-xl font-bold">Title</h2>
    <button class="px-4 py-2 bg-blue-500 text-white rounded-lg">Click</button>
</div>
```

### Customization
- Modify `tailwind.config.js` to add custom colors/fonts.
- Use `@apply` in CSS:
```css
.btn-primary {
    @apply px-4 py-2 bg-blue-500 text-white rounded-lg;
}
```

[🔙 Back to All Modules](/modules)