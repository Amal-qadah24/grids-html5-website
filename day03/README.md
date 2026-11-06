# Day 03 – CSS Foundations, Cascade & Box Model

**Grids Apps Full Stack Web Development Internship – Foundation Track**

## Overview

Day 03 focuses on styling a multi-page website using external CSS, understanding the CSS cascade and specificity, and applying the box model.

The project builds on the HTML5 website developed in Day 02, introducing a consistent visual design across multiple pages using CSS3.

## Learning Objectives

- Understand CSS selectors, cascade, specificity, and inheritance.
- Apply the CSS box model and `box-sizing`.
- Create reusable design tokens using CSS variables.
- Style typography, colors, backgrounds, and borders.
- Apply consistent styling to headers, hero sections, and cards.
- Style HTML forms, tables, and interactive elements.
- Use CSS pseudo-classes and transitions.
- Implement responsive layouts using media queries.
- Debug CSS specificity conflicts.

## Pages

| File | Description |
|---|---|
| `index.html` | Main homepage and navigation |
| `profile.html` | Academic and professional profile |
| `about.html` | Personal introduction and background |
| `services.html` | Services and comparison table |
| `blog.html` | Blog articles, images, audio, and video |
| `contact.html` | Contact and application form |
| `registration.html` | Registration form |

All pages share one external stylesheet to maintain a consistent design.

## Project Structure

```text
day03/
│
├── index.html
├── profile.html
├── about.html
├── services.html
├── blog.html
├── contact.html
├── registration.html
├── style.css
├── README.md
│
└── assets/
    ├── images/
    │   ├── img.jpg
    │   └── html5.svg
    │
    └── media/
        ├── learning-audio.mp3
        └── learning-video.mp4
```

## Design Theme

Design Theme: Purple / Dark Elegant

### Color Palette

- Violet Dark: #502D55
- Mauve: #935073
- Peach: #F6DBC0
- Cream: #F8F4E9
### Design Tokens

CSS custom properties are defined inside `:root` to manage:

- Color palette
- Background and surface colors
- Primary and secondary text colors
- Spacing system
- Container width
- Border radius
- Typography
- Transition effects

## CSS Features Used

### Selectors & Cascade

- Universal selector: `*`
- Element selectors: `body`, `header`, `section`, `footer`
- Class selectors: `.hero`, `.card`
- ID selectors: `#debug-intro`
- Grouping selectors
- Descendant and child selectors
- Pseudo-classes: `:hover`, `:focus`, `:focus-visible`

### Box Model

- `margin`
- `padding`
- `border`
- `width` and `max-width`
- `box-sizing: border-box`

### Typography & Colors

- Font families and font sizes
- Font weights and line height
- Text colors and backgrounds
- CSS custom properties
- Color inheritance

### Layout & Responsive Design

- Flexbox
- Maximum container width
- CSS transitions
- Hover effects
- Media queries
- Responsive adjustments for mobile screens

### Forms & Tables Styling

- Form inputs and labels
- Fieldsets and legends
- Buttons and textareas
- Tables, captions, headers, and cells
- Details and summary elements

## Required Work

**1. Create Design Tokens**

Defined reusable CSS variables for colors, spacing, typography, borders, and transitions.

**2. Style Header, Hero & Cards**

Applied consistent styling to the main website components using reusable CSS classes.

**3. Specificity Debugging Challenge**

Tested CSS specificity conflicts between element, class, and ID selectors to understand how the browser determines which style takes priority.

## Challenges

**Specificity Debugging Challenge**

Created conflicting CSS rules to understand selector priority and debug unexpected styling behavior.

Example:

- Element selector: `p`
- Class selector: `.debug-text`
- ID selector: `#debug-intro`

The ID selector has higher specificity than the class and element selectors.

## Deliverables

- External CSS stylesheet (`style.css`).
- Tokenized color palette and spacing system.
- Consistent styling across all website pages.
- Styled header, hero sections, and cards.
- CSS box model implementation.
- Specificity debugging challenge.
- No inline styles in the final HTML.



## Exit Ticket

1. **What did I build today?**

   Styled a multi-page HTML5 website using an external CSS stylesheet, with a consistent vintage-inspired design across all pages.

2. **What bug or difficulty did I solve?**

   Identified and resolved CSS cascade and specificity conflicts, and organized reusable design tokens to maintain consistent styling.

3. **What concept can I explain clearly?**

   CSS selectors, specificity, inheritance, the cascade, and the box model.

4. **What remains incomplete?**

   Further visual refinements and testing across different screen sizes and browsers.

---

**Training Track:** Full Stack Web Development  
**Day:** 03  
**Focus:** CSS Foundations, Cascade, Specificity & Box Model  
**Styling:** External CSS – CSS3  
**Theme:** Dark Purple / Elegant