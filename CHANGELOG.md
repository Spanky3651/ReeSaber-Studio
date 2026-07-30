# Changelog

All notable changes to ReeSaber Studio are documented here. This project loosely
follows [Keep a Changelog](https://keepachangelog.com/) and
[Semantic Versioning](https://semver.org/).

## [1.1.0] — 2026-07-30

### Added
- **Custom asset pipeline** — drag‑and‑drop upload of meshes (`.obj` / `.glb` / `.gltf`),
  textures (`.png` / `.jpg`), and sounds (`.wav` / `.ogg`) via `FileReader`; live preview
  in the 3D viewport; per‑module Custom Mesh and Custom Texture slots; assets embedded as
  base64 in the exported `BinaryAssets`.
- **In‑app documentation** — contextual `?` help cards on technical fields, a collapsible
  Quick Start guide, and accordion‑grouped control panels.
- **Starter templates** — Basic Neon Saber, Reactive Velocity Saber, and Custom Mesh Template.
- **QA tooling** — side‑by‑side live JSON inspector with syntax highlighting, enforced safe
  slider min/max with per‑panel *Reset to Safe Default*, real‑time validation, and a
  pre‑export check.
- Embedded SVG favicon matching the app theme.

## [1.0.0] — 2026-07-30

### Added
- Initial release: single‑file ReeSabers config generator & editor.
- Preset management (create / duplicate / rename / delete, hand assignment, colors).
- Module stack builder (Blade, Trail, Sparks, Distortion) with reorder / mute / delete.
- Driver builder with live response‑curve preview.
- Three.js live 3D preview.
- Import existing ReeSabers presets and export schema‑correct `0.3.18` JSON.
- Dark‑cyberpunk true‑black theme.

[1.1.0]: https://github.com/<your-username>/reesaber-studio/releases/tag/v1.1.0
[1.0.0]: https://github.com/<your-username>/reesaber-studio/releases/tag/v1.0.0
