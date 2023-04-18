# Responsive Design

- Understanding Responsive Design
- Working with Media Queries
- Creating a Side Drawer

## 1) Landing Page

- `<header id="main-header">` : flex, justify-content: space-between, align-items
  - `<a>` : text-decoration, text-transform
  - `<nav>`
    - `<ul>` : flex, list-style
    - `#main-header nav a:hover` : background-color

- `<main>`
  - `<h1>`
  - `<section id="latest-products">`
    - `<ul>`
      - `<li class="food-items">` : overflow: hidden;
        - `<article>`
          - `<img>` : height, width, object-fit
          - `<div class="food-item-content">`
            - `<h2>`
            - `<a class="btn">` : border-radius: 4px;

## 2) Comparing Units (specifically for font-size)

  - `px`
    - Easy to understand and translatable
      - Everyone knows pixels.
      - Pixels are consistent across all devices.
    - Limited user focus and not scalable
      - 10 px is 10 px for all widths, no matter the screen size
      - Customized size not available
  
  - `%`
      - Relative to parent element size
      - Hard to manage due to cascading nature

  - `em`
    - Size is relative to font-size
      - 1em = 100%, 2em = 200%
    - Hard to manage due to cascading nature

  - `rem`
    - Size is relative to root element's font size (HTML setting, browser setting)
      - 1rem = 100%, 2rem = 200%
    - Preferred choice, if applicable

## 3) Comparing Units (specifically for other properties)
  - `padding`
    - `%`
      - Relative to parent element size (content width) 
    - `em`
      - Relative to parent font size
    - `rem`
      - Relative to root font size

## 3) Desktop First vs Mobile First
  - `Desktop`
    - Traditional approach
    - Office based audience
    - Feature-rich website
  
  - `Mobile`
    - Functional approach
    - Lifestyle/news focused audience
    - Content first
