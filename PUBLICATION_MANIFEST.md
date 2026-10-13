# Publication Manifest

## Repository

- Owner: `aloycius`
- Repository: `book-keeping-f2-sb-adt`
- Visibility: public
- Purpose: ADT Studio conversion publication for `Book-keeping F2 SB`

## Included Initially

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
- Absolute local paths from the conversion machine

## Next Publication Gate

Before publishing converted book content, verify:

- The ADT output is semantic HTML, not page screenshots
- Every requested page has passed source-vs-output visual review
- Runtime assets load from a clean static server
- The publication tree contains no secrets, private paths, databases, or source PDFs
- Rights and license text are confirmed
