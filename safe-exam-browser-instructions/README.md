# Safe Exam Browser (Beyond EQAO) — V2.1 GitHub Pages Package

This package includes the V2 design plus a responsiveness fix for long filenames inside the **Core Configuration Files** and **Editable OneNote Templates** cards.

## Fix included

The CSS now:

- ensures the grid columns can actually shrink (`minmax(0, 1fr)`),
- prevents card/grid children from forcing overflow (`min-width: 0`),
- allows long `.seb` filenames to wrap cleanly (`overflow-wrap: anywhere; word-break: break-word;`), and
- collapses the two-column card layout to a single column on smaller viewports.

## Publish on GitHub Pages

1. Upload the package contents to a GitHub repository.
2. Go to **Settings > Pages**.
3. Choose **Deploy from a branch**.
4. Select your branch and the `/root` folder.
5. Save.
