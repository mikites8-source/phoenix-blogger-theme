# Changelog

## [Unreleased] — develop-v2 (2026-10-17)

### Fixed
- Corrected Blogger-rendered article and static-page HTML titles.
- Added label-specific and keyword-search titles; applied `noindex,follow` only to keyword-search pages.
- Removed duplicate Phoenix Open Graph declarations in favor of Blogger-native head metadata.
- Removed the unresolved/empty `WebSite.description` JSON-LD property.

### Validated on staging
- Blogger accepted the V2 XML at `almdmtest.blogspot.com`.
- Verified homepage, article, static page, label archive, and keyword-search title/canonical behavior.
- Confirmed keyword-search `noindex,follow` without inadvertently applying it to the label archive.
- Confirmed the updated WebSite/Organization JSON-LD no longer contains the defective description field.

### Pending
- Refine generic native Open Graph titles on label/search pages; retest with search descriptions enabled.
- Validate image/Twitter previews, full structured data, and remaining V2 release gates.

Notable changes to Phoenix are recorded here. Dates use `YYYY-MM-DD`.

## [1.0.0] - 2026-08-20

### Added

- Public installation and customization documentation.
- Third-party notices and a self-contained featured-image fallback.
- An official live-demo link to Alemondem.

### Changed

- Generalized publication branding and metadata for reuse.
- Tightened homepage section spacing.
- Corrected the homepage statistics section rendering.
- Clarified that `source/theme.xml` is the Blogger installation file.

### Removed

- Account-specific advertising and affiliate identifiers from repository history.
- Legacy and backup material with unresolved third-party provenance.
- External placeholder-image dependency.
- Duplicated, publication-specific release documentation.

### Security

- Rewrote reachable branch and tag history after sensitive identifier cleanup.
- Completed GitHub Support cleanup of obsolete hidden pull-request references.

## 1.0.0-rc1 - 2026-07-08

### Added

- Initial responsive homepage, navigation, card system, reading layout, footer, modular prototype assets, and Blogger XML integration.

[1.0.0]: https://github.com/mikites8-source/phoenix-blogger-theme/releases/tag/v1.0.0
