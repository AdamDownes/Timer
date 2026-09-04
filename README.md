# Sequence Timer PWA — Louder Cue Version

New in this version:

- Short beep
- Loud triple beep (default)
- Bell
- Cue style is remembered
- Cue style is saved inside presets
- Tries to use iOS web audio in playback mode when supported
- Service-worker cache version bumped so updates propagate more reliably

## Updating GitHub Pages

Replace the old files in your repository with the files from this ZIP, keeping the same filenames.

The most important files to replace are:

- index.html
- sw.js
- manifest.webmanifest

Also replace the icon files if you want everything to match exactly.

After committing the changes, GitHub Pages will redeploy automatically.

On iPhone, open the site in Safari and refresh it once. Then fully close and reopen the Home Screen app if it still shows the old version.
