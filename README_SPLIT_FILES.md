# How to split `terms_and_definitions.md` file into multiple files

## General info

- This file splits terms and definitions into separate files based on the term.
- This is done by creating a file for each term.
- The file name is based on the term. The content of the file is one term plus the definition of the term.
- The file path is added to the specs.json file so it is included in the index.html after render.
- The original glossary file is not changed, but is removed as an entry from the specs.json.
- If not exists the specs.json file is copied to specs.unsplit.json (one time back-up of `specs.json`).
- The `spec.json file will have multiple new entries, one entry per defined term. The file can grow large.

## How to split terms_and_definitions.md

Split `terms_and_definitions.md` into multiple files, one file per term:

```
npm run split
```

Create the glossary file (named `index.html`):

```
npm run render
```
