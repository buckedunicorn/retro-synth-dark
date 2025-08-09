# Changelog

All notable changes to **Retro Synth Dark** will be documented in this file.

## [1.1.0] - 2025-08-09
### Added
- New themes: Retro Synth Cyan, Retro Synth Sunset, Retro Synth Midnight, Retro Synth Matrix, and Retro Synth Market Monkey Heatmap (tribute to Market Monkey Terminal by Anthony De Meulemeester / anthdm). Links: https://marketmonkeyterminal.com/?ref=buckedunicorn • https://github.com/anthdm • https://x.com/anthdm
- Extensive, research-driven token color coverage and semantic token colors across many languages and stacks (JavaScript/TypeScript, React/JSX, Python, Go, Rust, Java, C/C++, C#, PHP, Ruby, SQL, Docker, GraphQL/SPARQL, HTML/CSS, JSON/YAML/TOML/INI, Zig/Nim/V/Carbon, GLSL/HLSL shaders, WebAssembly, Assembly, Kubernetes, Terraform/Ansible, Apache/Nginx, and more).
- New screenshots added to assets and showcased in README: `cyan-code.webp`, `market-monkey-code.webp`, `matrix-code.webp`, `midnight-code.webp`, `sunset-code.webp`.

### Changed
- Heatmap theme accents refined for a “hotter” feel: warmer text selection plus active panel and tab borders.
- Extension manifest updated to register all new variants and improved keywords/metadata.
- Package description updated to reflect the theme suite.

### Fixed
- Resolved theme lint/deprecation warnings: ensured `editorOverviewRuler.findMatchForeground` uses transparency and migrated `editorIndentGuide.background`/`activeBackground` to `background1`/`activeBackground1` where applicable.
- Fixed invalid JSON in Matrix theme that previously caused manifest validation to fail.

### Docs
- README major update: added Theme Variants gallery (Cyan, Sunset, Midnight, Matrix, Heatmap), a detailed Color Palette Reference for each variant, and a Special Tribute section with links to Market Monkey Terminal and Anthony De Meulemeester (anthdm). Clarified variant count and embedded new screenshots.

## [1.0.0] - 2025-08-04
### Added
- Initial public release!
- Full neon synthwave color palette for editor, sidebar, terminal, and UI.
- Custom Git integration colors.
- Enhanced search highlights and error/warning states.
- Pro font recommendations and icon theme suggestions.
- Marketplace banner, icon, and sponsorship link.
