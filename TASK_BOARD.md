# Task Board

> Phoenix V2 development tracking. The earlier Phoenix First Paint task snapshot is retained below for historical context.

## Completed — Session 1E (2026-10-17)
- [x] Commit SEO foundation patch to `develop-v2` (`9aa768d`).
- [x] Remove unresolved `WebSite.description` JSON-LD substitution (`44ec01d`).
- [x] Import V2 XML into separate Blogger staging blog (`https://almdmtest.blogspot.com/`).
- [x] Verify homepage HTML title, self-canonical, and Open Graph title/URL.
- [x] Verify article-specific HTML title and canonical on staging.
- [x] Verify static-page HTML title and canonical on staging.
- [x] Verify label archive title, canonical, and absence of keyword-search `noindex`.
- [x] Verify keyword-search title and `noindex,follow` on `/search?q=Phoenix`.
- [x] Verify corrected JSON-LD `WebSite` output without empty/unresolved `description`.

## Follow-up — not release-blocking for Session 1E
- [ ] P2: Improve generic Open Graph titles on label/search archives without duplicate tags.
- [ ] P2: Re-enable Blogger search descriptions on staging and recheck metadata and JSON-LD.
- [ ] P2: Audit social images and Twitter/X cards.
- [ ] P2: Review duplicate favicon declarations, empty theme-color tags, and Blogger `blog.ieCssRetrofitLinks` substitution comment.
- [ ] Review full structured-data validity and robots headers/settings in release readiness.

## Next — Session 2
- [ ] Design System Foundation: establish V2 tokens, typography, layout, responsive rules, and component conventions.
- [ ] Complete later V2 accessibility, performance, Blogger compatibility, and release gates before any production deployment.

## Historical task snapshot (pre-V2)
### In Progress
- Phoenix Header v2
- Phoenix Navigation

### Next
- Hero Section
- Blog Cards

### Backlog
- Sidebar
- Footer
- Accessibility
- Performance
