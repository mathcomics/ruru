# Contributing to Ruru

Thank you for wanting to add to this story. Here is how to submit a chapter.

## How it works

*Ruru* is published as an mdBook. All content lives in the `src/` folder. The table of contents is defined in `src/SUMMARY.md`. When a PR is merged to `main`, GitHub Actions automatically rebuilds and publishes the book to GitHub Pages.

## Steps to submit a chapter

1. **Fork** this repository and clone your fork locally.

2. **Create a chapter file** in the `src/` folder, e.g. `src/chapter_x.md`

3. **Register the chapter** in `src/SUMMARY.md`

4. **Preview locally** (optional but recommended):
   ```bash
   # Install mdBook: https://rust-lang.github.io/mdBook/guide/installation.html
   mdbook serve
   # Open http://localhost:3000
   ```

5. **Open a Pull Request** against the `main` branch. The PR template will remind you of the checklist.

## Content guidelines

- Chapters should fit the tone of the existing story — mythological and historical fiction, told in a sparse, precise style.
- A new chapter can extend an existing volume or bridge two volumes.
- Keep formatting simple: headings (`##`) for scene breaks, plain paragraphs for prose.
- If you are proposing a new volume, open an issue first to discuss it.

## Review process

The maintainer will read submissions for narrative fit and prose quality before merging. Feedback will be given in the PR comments.
