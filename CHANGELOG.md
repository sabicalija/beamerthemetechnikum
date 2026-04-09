# Changelog

All notable changes to the `beamerthemetechnikum` theme will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/), and this project adheres to [Semantic Versioning](https://semver.org/).

## [Unreleased]

## [0.2.0] - 2026-04-09

### Added

- Minted package integration for code highlighting (`config/minted.cfg`)
- `\inputsource` helper command for including source code with framed layout
- Restructured configuration: TikZ and CircuiTikZ configs moved to `config/` directory (`.cfg` extension)
- Algorithm2e configuration with theme-colored keywords, `algorithmdisplay` environment, and `\algocaption` command (`config/algorithm2e.cfg`)
- Timing diagram configuration with theme-colored signal styles for `tikz-timing` (`config/timing.cfg`)

### Changed

- Monospace font (NotoSansMono) now supports faux italic via `AutoFakeSlant = 0.2`
- Disabled default bipole current/voltage color overrides in CircuiTikZ configuration

## [0.1.0] - 2026-04-01

### Added

- Modular theme structure (inner, outer, color, font themes)
- Flexible title page system (centered, split, general layouts)
- FHTW corporate identity colors (green, blue, gray)
- Noto font family bundled with file-based font loading
- Unicode math font configuration
- Custom geometric bullet symbols for itemize
- TikZ-based frametitle and footline with gradient support
- TikZ and CircuiTikZ configuration modules
- Legend entry commands and variables environment
- Block title color configuration
- Footnote positioning above footer elements
- `\shadowedtext` command
- Configurable theme options (title style, navigation, footline)

[Unreleased]: https://github.com/sabicalija/beamerthemetechnikum/compare/v0.2.0...HEAD
[0.2.0]: https://github.com/sabicalija/beamerthemetechnikum/compare/v0.1.0...v0.2.0
[0.1.0]: https://github.com/sabicalija/beamerthemetechnikum/releases/tag/v0.1.0
