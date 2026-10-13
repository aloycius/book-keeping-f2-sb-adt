# Book-keeping F2 SB ADT Conversion

This repository is the public publication and handoff space for converting **Book-keeping F2 SB** with ADT Studio.

## Status

- Source PDF: `Book-keeping F2 SB.pdf`
- ADT book label: `book-keeping-f2-sb`
- PDF pages: 152
- Conversion status: not yet converted in this repository
- Public source PDF: not included
- License: not assigned; source/publication rights must be confirmed before publishing book content

## Conversion Tooling

The conversion is intended to use ADT Studio plus the ADT book conversion skill:

```bash
npx skills add https://github.com/kareeeeeeeeem/adt-book-conversion-skill --skill adt-book-conversion
```

Run the ADT Studio pipeline from an ADT Studio checkout, not from this publication repository:

```bash
pnpm pipeline book-keeping-f2-sb "/path/to/Book-keeping F2 SB.pdf" --books-dir "/path/to/adt-studio/books"
```

After conversion and page-by-page verification, publish only the self-contained static web bundle here. Do not publish source PDFs, SQLite databases, entity history, LLM logs, cache files, prompts, responses, API keys, debug screenshots, or local machine paths.

## Expected Publication Contents

When the conversion is complete, this repository should contain:

- Static HTML entry point and runtime assets
- Fonts, images, CSS, and JavaScript required by the generated book
- A concise README with conversion provenance
- License or rights notice once confirmed

## Source Handling

The source PDF is authoritative for content and layout, but it is intentionally excluded from this public repository. Keep durable ADT book state inside the ADT Studio book directory so the conversion remains reproducible and inspectable.
