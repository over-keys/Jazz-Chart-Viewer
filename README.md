# Jazz Chart Viewer

A static browser application for importing and displaying iReal Pro chord-chart data. It can be hosted on GitHub Pages or opened directly from `index.html` after downloading the files.

## GitHub Pages deployment

Place all files and folders in this directory at the root of the selected GitHub Pages publishing source. Keep `index.html` and the included `.nojekyll` file at that root.

No build step, package installation, or server-side processing is required.

## Use

1. Open the published site or `index.html`.
2. Choose **Import**.
3. Paste an `irealb://` or `irealbook://` shared string, or select a saved text or HTML file.
4. Search for a song and choose Original or Expanded view.

Imported song data and display settings are stored in the browser. Song source data is stored compactly and parsed again when the application starts.

## Files

- `index.html`: application
- `help.html`: Japanese help
- `help.en.html`: English help
- `help.css`: help-page styles
- `LICENSE`: application license
- `THIRD_PARTY_NOTICES.md`: third-party notices
- `licenses/`: third-party license texts

MuseJazz Text is loaded from its online source when available. When it cannot be loaded, the application uses fallback fonts and Unicode symbols.
