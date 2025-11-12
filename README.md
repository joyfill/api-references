## API References

This repository hosts API reference documentation for two platforms, served via a single GitHub Pages site.

### Structure
- `kotlin/`: Kotlin/JVM reference (e.g., Dokka output)
- `ios/`: iOS (Swift) reference (e.g., DocC static site)
- `index.html`: Landing page linking to each platform's docs

### Viewing
- On GitHub Pages: enable Pages for this repository and point it at the root (or wherever `index.html` lives).

### Updating documentation
1. Regenerate the platform docs with your usual tool (Dokka, DocC, etc.).
2. Replace the contents of the corresponding directory: `kotlin/` or `ios/`.
3. Open a pull request with the changes. When merged, GitHub Pages will serve the updated docs.

### Notes
- Each platform directory should include an `index.html` so links from the landing page resolve correctly.
- Links are relative; directory names must remain `kotlin/` and `ios/`.

Questions or issues? Open an issue in this repository.
