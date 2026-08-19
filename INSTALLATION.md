# Installation

## Before you begin

- Use a test blog before changing a production site.
- Back up your current Blogger theme.
- Save any custom widget HTML or settings that you may need to restore.

## Install the theme

1. Download [`source/theme.xml`](source/theme.xml).
2. Sign in to Blogger and select the target blog.
3. Open **Theme**.
4. Use the menu beside **Customize** and select **Backup**. Keep the downloaded backup in a safe place.
5. Open the same menu, select **Restore**, and upload `source/theme.xml`.
6. Open **Layout** and configure the Page List, Featured Post, and other enabled widgets.
7. Open **Settings** and confirm the title, description, language, favicon, and search visibility are correct for your site.

## Verify the installation

Check the following in a private or test blog:

- Homepage and featured story
- Navigation and mobile menu
- One post with and without an image
- One static page
- Label, archive, and search pages
- Footer links and copyright text
- Page title, description, canonical URL, and social metadata
- Keyboard navigation and mobile layout

The Featured Story panel displays a built-in visual fallback when a selected post has no usable image.

## Roll back

If the theme does not work as expected, return to **Theme > Restore** and upload the backup created before installation. Restoring a theme does not restore deleted posts or pages.

## Development files

Only `source/theme.xml` is uploaded to Blogger. `source/index.html`, `source/css/`, and `source/js/` are development references and are not a multi-file Blogger installation package.
