# Phoenix Blogger Theme

# Customization Guide

**Version:** 1.0.0

**Status:** Stable

**Project:** Phoenix Blogger Theme

**Website:** Alemondem

---

# Overview

Phoenix Blogger Theme is designed around the **Phoenix Design System**, allowing most visual customization without changing the theme architecture.

This guide explains how to customize Phoenix while maintaining compatibility with future updates.

---

# Customization Philosophy

Always prefer:

- Blogger Settings
- Blogger Widgets
- CSS Variables

Avoid editing the core Blogger XML unless absolutely necessary.

This approach makes upgrading to future Phoenix versions much easier.

---

# Theme Identity

## Blog Title

Configure in Blogger:

```
Settings

↓

Basic

↓

Title
```

Example

```
Alemondem
```

---

## Blog Description

Example

```
Discover the Best in Digital Entertainment, Technology & Creative Innovation.
```

---

## Logo

Location

```
Layout

↓

Header Widget
```

Recommended

- SVG
- PNG
- Transparent background

---

## Favicon

Recommended

- PNG
- 512 × 512 px

Configure in:

```
Settings

↓

Favicon
```

---

# Navigation

Phoenix uses Blogger's native PageList widget.

Location

```
Layout

↓

PageList
```

Example Navigation

- Home
- Artificial Intelligence
- UI/UX
- Marketing
- About

Navigation automatically updates when pages are added or removed.

---

# Homepage Hero

The homepage hero can be customized by editing the Hero section in the theme.

Recommended content

Headline

A clear statement describing your website.

Example

```
Helping Creators Build Better Digital Experiences
```

Description

Explain what visitors will find.

Primary Button

```
Explore Articles
```

Secondary Button

```
About Alemondem
```

---

# Homepage Categories

Recommended categories

- Artificial Intelligence
- UI/UX Design
- Digital Marketing
- Technology
- Branding
- Tutorials

Choose categories that reflect your site's focus.

---

# Colors

Phoenix uses centralized design tokens.

Recommended customization method:

Modify CSS variables instead of editing individual CSS rules.

Primary colors include:

- Primary
- Primary Dark
- Secondary
- Accent
- Background
- Surface
- Border
- Text

Changing these variables updates the entire design consistently.

---

# Typography

Default Font

```
Inter
```

Recommended replacements

- Manrope
- Plus Jakarta Sans
- Poppins
- IBM Plex Sans

Avoid mixing multiple font families.

---

# Buttons

Phoenix includes two button styles.

Primary

Used for important actions.

Examples

- Subscribe
- Explore Articles

Secondary

Used for supporting actions.

Examples

- About
- View All

Maintain consistent button usage throughout the site.

---

# Author Card

The Phoenix Author Card can be customized.

Editable content

- Author name
- Position
- Biography
- Call-to-action buttons

Recommended biography length

40–70 words

Recommended buttons

- About Me
- All Articles

---

# Footer

Recommended sections

Categories

Resources

Company

Social Links

Copyright

Keep footer navigation concise.

---

# Newsletter

Phoenix includes a newsletter interface.

Supported providers

- Mailchimp
- Brevo
- Beehiiv
- ConvertKit
- EmailOctopus
- Google Apps Script

The user interface is intentionally separated from provider integration.

---

# Images

Recommended sizes

Featured Image

```
1600 × 900 px
```

Hero Images

```
1920 × 1080 px
```

Author Photo

```
400 × 400 px
```

Always use optimized images.

---

# Icons

Recommended icon libraries

- Heroicons
- Lucide
- Tabler Icons

Maintain consistent icon style throughout the theme.

---

# Accessibility

Do not remove:

- ARIA labels
- Alt attributes
- Keyboard navigation
- Semantic headings

Accessibility is a core part of Phoenix.

---

# Responsive Design

Phoenix automatically supports

Desktop

Tablet

Mobile

Avoid adding fixed widths.

Use flexible layouts whenever possible.

---

# Blogger Widgets

Recommended widgets

- Header
- Blog
- PageList
- HTML
- Profile
- Feed

Avoid excessive third-party widgets that negatively affect performance.

---

# Performance Recommendations

Use

- Optimized images
- Minimal JavaScript
- Lightweight embeds
- Lazy loading where appropriate

Avoid

- Multiple animation libraries
- Heavy sliders
- Unnecessary plugins

---

# SEO Recommendations

Configure

- Blog Title
- Blog Description
- Image Alt Text
- Search Description
- Labels
- Meta Description

Submit

- Sitemap
- robots.txt
- Search Console

---

# Safe Customization

Recommended

✓ CSS Variables

✓ Blogger Widgets

✓ Theme Settings

✓ Images

✓ Navigation

✓ Typography

Avoid

✗ Removing Blogger widgets

✗ Editing Blogger core includables without backups

✗ Removing accessibility attributes

✗ Hardcoding colors throughout the CSS

---

# Before Updating Phoenix

Always

1. Backup your current theme.

2. Export Blogger XML.

3. Read the CHANGELOG.

4. Apply customizations again if necessary.

---

# Future Customization

Future Phoenix versions will include

- Theme color presets
- Dark Mode
- Homepage Builder
- Mega Menu
- Reading Preferences
- Additional Layout Options

---

# Best Practices

Keep the design clean.

Maintain visual consistency.

Prefer readability over decoration.

Customize through the design system whenever possible.

---

# Support Documentation

Additional documentation is available in

```
docs/
└── Phoenix Blogger Theme v1.0.0 Release Dossier/
```

See

- Product Specification
- Installation Guide
- Architecture Summary
- Release Manifest
- QA Report
- Roadmap
- Changelog

---

Phoenix Blogger Theme

Version

```
1.0.0
```

Status

```
Stable
```

© Phoenix Blogger Theme Project
