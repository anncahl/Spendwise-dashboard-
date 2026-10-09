# SpendWise Dashboard Shell

A modern, responsive dashboard interface layout built as part of the Web Development Fundamentals coursework.

## Overview
This project establishes the visual layout and foundation for the SpendWise capstone project using semantic HTML5 and modern CSS techniques (CSS Grid & Flexbox).

## Features Implemented
1. **CSS Grid Main Structure**: Used CSS Grid to create a 2-column dashboard layout (Sidebar + Main Content Area) and a responsive category card grid.
2. **Flexbox Layouts**: Used Flexbox to arrange items inside the navigation menu, header user profile, and category card contents.
3. **CSS Custom Properties (Variables)**: Defined theme variables (`:root`) for brand color, accent color, background, surface, and text colors.
4. **Responsive Design**: Included a media query (`@media (max-width: 768px)`) to collapse the layout into a single column for mobile devices.
5. **Card Micro-interactions**: Added subtle hover and focus animations using `transform` and `box-shadow` with transitions under 250ms.
6. **Dark Theme Support (Stretch Goal)**: Integrated `prefers-color-scheme: dark` to automatically adjust variables based on system settings.

## Files
- `index.html` - Semantic HTML layout structure.
- `style.css` - Custom styles, grid, flexbox, variables, and media queries.
- `README.md` - Documentation explaining the structure and design decisions.
