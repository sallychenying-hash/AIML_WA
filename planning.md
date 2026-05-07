# Planning Document

## 1. Website Purpose

The purpose of this website is to document my courseworks in AIML. The target audience includes teachers, classmates, and my future self.

## 2. Target Audience

- Teachers
- Classmates
- My future self
  
## 3. Content Plan

The website includes:

- A homepage introducing the documentation portfolio
- An overview page summarising all projects
- Separate project pages for language detector, and digit recognizer
- Supporting written documents: README and planning

## 4. Navigation Structure

- Home (`index.html`)
- About (`about.html`)
- Language (`language.html`)
- Digits (`digits.html`)

## 5. Wireframe Sketch

- `HEADER`: Logo | Nav: Overview 
- `HERO`: Big heading + subtitle + button
- `ABOUT SECTION`: Short description of the website
- `CARD GRID`: Language | Digits
- `FEATURES LIST`: Semantic HTML, tables, code blocks
- `FOOTER`: Own your compass

## 6. Design Decisions

### Colours

- Primary: `#47275B` — used for header, footer, and contact section
- secondary: gradient `linear-gradient(90deg, #8A6B35, #8A357D, #35518A)` — used for hero background
- Accent: gradient `linear-gradient(0deg, #6200FF, #60EFFF)` — used for links, buttons, and highlights
- Background: `#FAF9F8` — used for page body

### Typography

- Font family: `"Segoe UI", Tahoma, Geneva, Verdana, sans-serif`
- Base font size: browser default (16px)
- Headings use `font-weight: 700` and scaled sizes
- Line height: `1.6` for readability

### Layout

- Max content width: `1100px` centered with `margin: 0 auto`
- Flexbox used for header layout
- CSS Grid used for card layout on homepage
- Sticky header so navigation stays visible while scrolling

## 7. Tools Used

- VS Code — code editor
- Git and GitHub — version control and repository hosting
- GitHub Pages — free static site hosting

## 8. HTML Tags Used and Why

| Tag | Reason |
|---|---|
| `<header>` | Wraps the site header and navigation |
| `<nav>` | Marks the navigation links for accessibility |
| `<main>` | Wraps the main content of each page |
| `<article>` | Wraps self-contained project documentation |
| `<section>` | Groups related content within a page |
| `<footer>` | Marks the bottom of the page with copyright info |
| `<table>` | Displays test results and comparisons |
| `<pre><code>` | Shows formatted Python code examples |
| `<figure>` | Wraps images with semantic meaning |

## 9. CSS Properties Used and Why

| Property | Reason |
|---|---|
| `font-family` with fallbacks | Ensures text renders consistently across operating systems |
| `border-radius` | Rounds corners on cards and buttons for a modern look |
| `position: sticky` | Keeps the header visible as the user scrolls |
| `transition` | Adds smooth hover animations on buttons and links |
| `display: grid` | Creates a responsive card layout on the homepage |
| `display: flex` | Aligns header logo and navigation side by side |
| CSS custom properties (`--var`) | Makes colours and spacing easy to update consistently |
