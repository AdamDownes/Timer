# Sequence Timer PWA — Preset Version

New features:

- Save named presets.
- Load presets later.
- Overwrite an existing preset.
- Delete presets.
- Presets survive closing and reopening the app.
- The current unsaved timer setup is also restored automatically.
- Continuous or manual-advance mode is saved with each preset.
- Sound on/off is saved with each preset.

Presets are stored using browser localStorage. They stay on the same browser/device unless site data is cleared.

## Test locally

Run this command inside this folder:

    python -m http.server 8000

Then open:

    http://localhost:8000

## Updating an installed iPhone PWA

If this replaces an earlier hosted version, upload all of the new files to the same host.
Safari may briefly show a cached version. Closing and reopening the Home Screen app, or refreshing the site in Safari, will normally pick up the new service worker version.
