# GitKraken Browser Extension: product notes for the docs-authoring skill

This folder is **local to this docs repo**. The shared skill files (SKILL.md,
references/, scripts/) are owned by GK-WP-HC-Design and replaced on every
distribution; `product/` never is. Edit it here.

| | |
| --- | --- |
| Content folder | `browser-extension/` (images in `_images/`) |
| WordPress category | `browser-extension`: pages publish at `/browser-extension/<slug>/` |
| Home page | `browser-extension-home` (`page_type: main-index`) |
| Nav file | `GK-WP-HC-Plugin/config/products/browser.json` in GK-WP-HC-Design: label-only groups and links |
| Nav depth | up to 5 levels |
| Right-hand TOC | H2 and H3 |
| Unlabelled code panels | "Code" |

`config.json` beside this file holds the same facts in the form
`scripts/check_pages.py` and GK-WP-HC-Design's `preview/` read.

## Metadata (FRONTMATTER-SCHEMA.md)

The metadata check is off for this help center (see `config.json`).

## Decisions for this help center

The settled design decisions are in GK-WP-HC-Design
`redesign-expansion/PER-PRODUCT-DECISIONS.md`, section "GitKraken Browser Extension". Record
conventions that only apply here (naming, recurring page shapes, words to use)
below this line.
