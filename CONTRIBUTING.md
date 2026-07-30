# Contributing to ReeSaber Studio

Thanks for your interest in improving ReeSaber Studio! This is a small, dependency‑free project, so contributing is refreshingly simple.

## Ground rules

- **The app is one file.** All HTML, CSS, and JavaScript live in `index.html` (and its identical twin `ReeSaber-Config-Generator.html`). There is no build step, no bundler, and no npm install to run the app.
- **Keep it self‑contained.** The only external dependency is Three.js via CDN. Please don't introduce a build system or package dependencies without opening an issue to discuss it first.
- **Match the style.** Vanilla JS, the existing helper patterns (`field()`, `accordion()`, `slider()`, etc.), and the dark‑cyberpunk theme variables defined in `:root`.

## Making a change

1. Fork the repo and create a branch: `git checkout -b my-feature`.
2. Edit `index.html`. If you change it, copy the same content into `ReeSaber-Config-Generator.html` so the two entry points stay identical (or update your PR description noting which is canonical).
3. **Test in a browser.** Open the file and verify:
   - No errors in the DevTools console.
   - Your change works, and existing flows still work (create/duplicate/delete preset, add modules, add a driver, upload an asset, import + export JSON).
   - Exported JSON still parses and round‑trips through **Import**.
4. Commit with a clear message and open a pull request describing what changed and why.

## Good first contributions

- New contextual help entries (the `HELP` map) for fields that don't have one yet.
- Additional starter templates (`STARTERS`).
- Refining the exported schema against a **real** ReeSabers sample (see the note in the README). If you have a genuine export using a feature Studio doesn't model perfectly, attaching it to an issue is hugely helpful.
- UI/accessibility polish.

## Reporting bugs

Open an issue with:

- What you did, what you expected, and what happened.
- Your browser and OS.
- If it's an export/import problem, attach the JSON (a Studio project export captures the full state).

By contributing, you agree that your contributions are licensed under the project's [MIT License](LICENSE).
