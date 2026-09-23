# Frontend Mentor — Order Summary Component

This is my solution to the [Order Summary Component challenge](https://www.frontendmentor.io/challenges/order-summary-component-QlPmajDUm).

## Overview

### The challenge

The goal is to build an order summary card and make it as close as possible to the provided design.

Users should be able to:

* View the order summary component on different screen sizes.
* See responsive layouts for mobile and desktop.
* Interact with the links and buttons through hover states.

### Screenshot

![Order Summary Component](./design/desktop-design.jpg)

## Built with

* Semantic HTML5
* CSS3
* CSS custom properties
* CSS nesting
* Flexbox
* Responsive design
* Mobile-first approach
* BEM naming convention

## What I learned

While building this challenge, I practiced:

* Structuring a component with semantic HTML.
* Using BEM to organize CSS class names.
* Creating responsive layouts with media queries.
* Using Flexbox to align and distribute elements.
* Using CSS custom properties for reusable colors.
* Working with pseudo-elements and hover states.
* Managing a mobile-first CSS architecture.
* Using `overflow: hidden` with `border-radius` to clip child elements.
* Using `margin-left: auto` to push an element to the right inside a Flexbox container.

## Useful CSS concepts

### BEM

The component uses a BEM-inspired naming convention:

```text
order-card
order-card__hero
order-card__content
order-card__title
order-card__description
```

This makes the relationship between the component and its elements clearer.

### Flexbox

The annual plan uses Flexbox to align the icon, plan information, and change link:

```css
.annual-plan {
    display: flex;
    align-items: center;
}
```

The `Change` link is pushed to the right with:

```css
.annual-plan__change {
    margin-left: auto;
}
```

## Continued development

For future challenges, I want to continue improving:

* Responsive design
* CSS layout techniques
* Accessibility
* Semantic HTML
* CSS architecture
* Writing clean and maintainable CSS

## Author

* GitHub — [Alexandre DELSOL](https://github.com/alexandre-delsol)
* Frontend Mentor — [@alexandre-delsol](https://www.frontendmentor.io/profile/alexandre-delsol)

## Acknowledgments

Challenge provided by [Frontend Mentor](https://www.frontendmentor.io/).
