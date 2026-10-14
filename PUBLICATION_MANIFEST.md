# Publication Manifest

## Repository

- Owner: `aloycius`
- Repository: `book-keeping-f2-sb-adt`
- Visibility: public
- Purpose: ADT Studio static web publication for `book-keeping-f2-sb`

## Included

- Static HTML entry point and page files
- ADT runtime assets, styles, fonts, images, and content catalogs
- `imsmanifest.xml`
- `README.md`
- `PUBLICATION_MANIFEST.md`
- `.gitignore`

## Excluded

- Source PDF files
- ADT Studio book databases
- Entity versions and book-local cache data
- LLM prompts, responses, logs, and cost records
- API keys, tokens, `.env` files, and credentials
- Debug screenshots and temporary audit renders
- Source maps and local agent instructions
- Absolute local paths from the conversion machine

## Verification

- ADT pipeline completed for 152 source pages.
- Static bundle copied from the ADT package directory with `AGENTS.md` and source maps excluded.
- Publication tree should be served from a static web server rooted at the repository root.
