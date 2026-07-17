# Add Quiz 2 to the HTML Catalog

## Goal

Make `小测2_题目与详解_公式修正版.html` accessible from `content.html`.

## Design

Append one catalog `<article>` to the end of the existing `<main>` content. The entry will follow the page's established structure exactly:

- Display title: `小测 2｜题目与详解（公式修正版）`
- “单独打开” link to `小测2_题目与详解_公式修正版.html`
- Lazy-loaded iframe preview of the same file
- Matching iframe title for accessibility

No styles, scripts, or unrelated catalog entries will change.

## Verification

Confirm that the target file exists, the new filename appears exactly twice in `content.html` (link and iframe), and the new article is inside `<main>` before its closing tag.
