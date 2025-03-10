# HTML & CSS Basics

## **Core Concepts**
- **HTML Structure**: Tags, attributes, semantic elements (`<header>`, `<article>`, `<section>`).
- **CSS Fundamentals**: Selectors, box model, positioning, and specificity.
- **Responsive Design**: Media queries for breakpoints (e.g., `@media (max-width: 768px)`).

---

## **Modern Layout Techniques**
### **Flexbox**
- Align items horizontally/vertically.
- Example:
  ```css
  .container {
    display: flex;
    justify-content: center;
    gap: 20px;
  }
  ```

### **CSS Grid**
- Create complex layouts with rows and columns.
- Example:
  ```css
  .grid-container {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
  }
  ```

---

## **Best Practices**
- Use `rem`/`em` units for scalability.
- Mobile-first approach for responsiveness.
- Validate HTML with [W3C Validator](https://validator.w3.org/).

[🔙 Back to Module 1](/modules/01-frontend-fundamentals)
```

---

**File**: `modules/01-frontend-fundamentals/bootstrap.md`  
```markdown
# Bootstrap 5 Essentials

## **Key Features**
- **Grid System**: Responsive 12-column grid (e.g., `.col-md-6`).
- **Components**: Pre-built navbars, cards, modals, and forms.
- **Utilities**: Spacing (`.mt-3`), text alignment (`.text-center`), and flex utilities.

---

## **Example: Grid Layout**
```html
<div class="container">
  <div class="row">
    <div class="col-sm-12 col-md-6">Column 1</div>
    <div class="col-sm-12 col-md-6">Column 2</div>
  </div>
</div>
```

---

## **Customization**
- Override Bootstrap variables via `scss`.
- Use [Bootstrap Icons](https://icons.getbootstrap.com/) for vector icons.

[🔙 Back to Module 1](/modules/01-frontend-fundamentals)
```

---

**File**: `modules/01-frontend-fundamentals/tailwind.md`  
```markdown
# Tailwind CSS: Utility-First Approach

## **Core Principles**
- **Utility Classes**: Directly style elements (e.g., `bg-blue-500`, `p-4`).
- **Responsive Design**: Prefix utilities with breakpoints (e.g., `md:text-center`).
- **Customization**: Extend `tailwind.config.js` for themes.

---

## **Example: Styled Button**
```html
<button class="px-4 py-2 bg-indigo-600 text-white rounded-lg hover:bg-indigo-700">
  Click Me
</button>
```

---

## **Best Practices**
- Use `@apply` to extract repeated utilities into CSS classes.
- Purge unused styles for production builds.

[🔙 Back to Module 1](/modules/01-frontend-fundamentals)