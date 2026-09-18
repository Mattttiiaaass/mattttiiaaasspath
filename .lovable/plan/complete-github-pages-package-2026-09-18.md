# Complete GitHub Pages package

## Build
- Update the normal website to use both newly uploaded Fortnite asset lists.
- Bring the standalone page up to feature parity with All/New selection and file-type filters.
- Make the downloadable copy self-contained, using the included compressed data files instead of missing external files.
- Include the logo, installable-app manifest, Discord verification file, and GitHub Pages publishing workflow.
- Add a second workflow file containing the full page markup, so the page also exists inside a `.yml` as requested.

## Verify and deliver
- Check both asset lists decompress and load, test the standalone page on phone and desktop sizes, inspect the archive contents, and provide a fresh ZIP.

## Technical details
- GitHub Actions will assemble and publish the static site from the included files.
- The archive will exclude dependencies, generated output, and Git history.
