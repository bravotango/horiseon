# Horiseon: HTML & CSS Code Refactor

## Project Goal

**Refactoring** existing code (improving it without changing what it does) to meet a certain set of standards or to implement a new technology is a common task for front-end and junior developers. For this particular homework assignment, a marketing agency has hired you to refactor an existing site to make it more accessible.

An increasingly important consideration for businesses, web **accessibility** ensures that people with disabilities can access a website using assistive technologies like video captions, screen readers, and braille keyboards. Accessibility is good for business&mdash;for one thing, accessible sites rank higher in search engines like Google. It also helps companies avoid litigation, which might arise if people with disabilities can't access a website.

Accessibility can include complex requirements, but your tech lead has given you a small list of specific criteria for this project. These criteria are documented in the Acceptance Criteria section.

To impress clients, you should always exceed expectations and improve the codebase for long-term sustainability. For example, check that all links are functioning correctly. You can also increase the efficiency of the CSS by consolidating the selectors and properties, organizing them to follow the semantic structure of the HTML elements, and including comments before each element or section of the page.

## User Story

```
AS A marketing agency
I WANT a codebase that follows accessibility standards
SO THAT our own site is optimized for search engines
```

## Acceptance Criteria

```
GIVEN webpage meets accessibility standards

WHEN I view the source code
THEN I find semantic HTML elements

WHEN I view the structure of the HTML elements
THEN I find that the elements follow a logical structure independent of styling and positioning

WHEN I view the icon and image elements
THEN I find accessible alt attributes

WHEN I view the heading attributes
THEN they fall in sequential order

WHEN I view the title element
THEN I find a concise, descriptive title
```

## Final Screenshot

![Alt text](./horiseon.png)

## Refactor Enhancements

1. Replaced appropriate div tags with semantic HTML 5 tags: header, footer, nav, main, aside, section.

2. Added media query to support mobile and tablet views with responsive design.

3. Leveraged SCSS for simplicity & consistency in CSS file.

4. Organized SCSS/CSS file and added comments for easy browsing

5. Improved title and fixed navigation link.

6. Leveraged JavaScript Date to keep the footer date current.

## Web Location

[https://bravotango.github.io/Horiseon-Code-Refactor/](https://bravotango.github.io/Horiseon-Code-Refactor/)

---
