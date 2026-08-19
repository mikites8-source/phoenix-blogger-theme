# Customization

## Recommended workflow

1. Back up the current theme.
2. Make one change at a time in a test blog.
3. Verify desktop and mobile layouts before applying the change to production.

## Blogger controls

- **Theme > Customize:** colors, backgrounds, and supported theme variables.
- **Layout:** navigation, Featured Post, publication text, and other widget content.
- **Settings:** blog title, description, language, favicon, and search settings.

## Navigation and links

Configure the Page List widget for primary navigation. Confirm every menu, footer, category, and call-to-action link points to a page that exists on your blog. Remove unused destinations rather than leaving placeholder links.

## Featured story

Choose the featured content through Blogger's Featured Post widget. If that post has no usable image, Phoenix displays its built-in Featured Story fallback instead of requesting an external placeholder service.

## Newsletter

The included newsletter interface does not submit to a mailing service by default. Connect it to a provider only after reviewing that provider's privacy, consent, and data-handling requirements. Remove or hide the interface if it is not configured.

## Source-level edits

The installable template is `source/theme.xml`. Keep a clean copy before editing. Blogger templates require valid XML, including escaped special characters and correctly nested tags. Re-upload and test the complete file after every source-level change.

The modular files beside the template support development and documentation; changes to them do not automatically update `source/theme.xml`.
