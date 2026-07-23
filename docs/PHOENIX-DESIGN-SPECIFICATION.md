# Phoenix Design Specification
Version: 1.0
Project: Phoenix Blogger Theme
Status: Active

---

# Vision

Phoenix transforms Blogger into a modern digital publication while preserving Blogger's native rendering engine.

Blogger manages the content.

Phoenix manages the experience.

---

# Design Principles

## 1. Blogger Owns the Data

Never replace Blogger rendering.

Phoenix only enhances presentation.

---

## 2. Component-Driven Design

Pages are assembled from reusable components.

Never redesign the same UI twice.

---

## 3. Consistent User Experience

Every page must share:

- Typography
- Colors
- Buttons
- Cards
- Spacing
- Navigation
- Footer

---

## 4. Responsive by Default

Every component must support:

- Desktop
- Tablet
- Mobile

---

# Component Library

## Global

- Header
- Navigation
- Search
- Newsletter
- Footer
- Advertisement

---

## Layout

- Hero Banner
- Page Header
- Section Header
- CTA Banner
- Information Grid
- Statistics
- Timeline
- Feature Cards
- Category Cards

---

## Blog

- Article Card
- Featured Article
- Related Articles
- Author Card
- Comments
- Breadcrumbs

---

# Templates

## Publication Page

Used for

- About
- Contact
- Privacy
- Terms

Structure

Header

↓

Hero

↓

Content

↓

Information

↓

CTA

↓

Newsletter

↓

Footer

---

## Category Landing

Used for

- Artificial Intelligence
- UI/UX
- Digital Marketing
- Web Development

Structure

Header

↓

Hero

↓

Featured Article

↓

Recent Articles

↓

Resources

↓

CTA

↓

Newsletter

↓

Footer

---

## Single Article

Header

↓

Hero

↓

Article

↓

Author

↓

Related Articles

↓

Comments

↓

Newsletter

↓

Footer

---

## Collection Template

Used for

- Search
- Labels
- Archive

Header

↓

Collection Header

↓

Article Grid

↓

Pagination

↓

Newsletter

↓

Footer

---

# Typography

Hero
48–56px

Section Titles
32px

Card Titles
24px

Body
18px

Reading Width
760–820px

Line Height
1.7

---

# Color Palette

Primary Blue

Secondary Blue

Accent Cyan

Neutral Gray

White Surface

Light Background

---

# Dynamic Content

Powered by Blogger

- Posts
- Pages
- Labels
- Search
- Archive
- Comments

Powered by Phoenix

- Hero
- CTA
- Newsletter
- Footer
- Cards
- Layout

---

# Editorial Standards

Every article should

- Solve one problem
- Be practical
- Be research-driven
- Use meaningful headings
- Include a conclusion
- Encourage continued reading

---

# Development Workflow

Specification

↓

Components

↓

Templates

↓

Implementation

↓

Testing

↓

Publish

---

# Definition of Done

A page is complete when

- Blogger renders correctly
- Responsive
- Accessible
- Uses approved Phoenix components
- Performance optimized
- Consistent with design system