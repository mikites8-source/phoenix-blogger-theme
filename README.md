# Phoenix Blogger Theme

Phoenix is a responsive, accessible Blogger theme for publications, creator blogs, and digital magazines. It uses native Blogger widgets and a self-contained XML template; no build process is required to install it.

> **Release status:** v1.0.0 is being prepared. The repository remains private while the final release audit is completed.

## Features

- Responsive desktop, tablet, and mobile layouts
- Native Blogger post, page, label, search, and archive support
- Configurable navigation, featured post, topic links, and footer
- Accessible keyboard navigation and reduced-motion support
- SEO, Open Graph, and structured metadata
- Self-contained featured-image fallback
- Vanilla JavaScript with no required runtime framework

## Install on Blogger

1. In Blogger, open **Theme**, use the menu beside **Customize**, and select **Backup**.
2. Download [`source/theme.xml`](source/theme.xml) from this repository.
3. In Blogger, open **Theme** again, choose **Restore**, and upload `source/theme.xml`.
4. Open **Layout** and configure the Page List, Featured Post, and other visible widgets.
5. Review the homepage, a post, a static page, a label page, and search on desktop and mobile.

See [INSTALLATION.md](INSTALLATION.md) for the complete checklist and rollback instructions.

## Customize

Use Blogger's **Theme > Customize** controls first. Widget content and links are managed in **Layout**. For source-level changes, edit `source/theme.xml`; the files in `source/css/` and `source/js/` support the standalone prototype and are not uploaded separately to Blogger.

See [CUSTOMIZATION.md](CUSTOMIZATION.md) for supported options and safe editing guidance.

## Repository layout

```text
source/
  theme.xml        Installable Blogger theme
  index.html       Standalone development prototype
  css/             Prototype styles
  js/              Prototype scripts
docs/              Architecture and implementation reference
CHANGELOG.md        Release history
LICENSE             MIT license
THIRD_PARTY_NOTICES.md
```

## Development preview

The standalone prototype can be served locally from `source/index.html`. It is useful for visual development, but Blogger-specific widgets and template expressions must be tested in a Blogger test blog using `source/theme.xml`.

## Demo

An official public demo is not yet published. Screenshots or third-party sites should not be treated as the canonical release; the installable file in this repository is the source of truth.

## Known limitations

- The newsletter form is presentation-only until the site owner connects a subscription provider.
- Navigation destinations and publication content must be configured by the site owner.
- Blogger may rewrite or proxy uploaded post images.
- Dark mode is not included in v1.0.0.

## License and third-party services

Phoenix is available under the [MIT License](LICENSE). External fonts, icons, Blogger services, and optional integrations are described in [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

## Author

Created by **Mikiyas Tesfaye**.
