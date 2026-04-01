# Changelog

All notable changes to the `beamerthemetechnikum` theme will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/), and this project adheres to [Semantic Versioning](https://semver.org/).

## [Unreleased]

### Added
- Minted package integration for code highlighting (`config/minted.cfg`)
- `\inputsource` helper command for including source code with framed layout
- Restructured configuration: TikZ and CircuiTikZ configs moved to `config/` directory (`.cfg` extension)

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

[Unreleased]: https://github.com/sabicalija/beamerthemetechnikum/compare/v0.1.0...HEAD
[0.1.0]: https://github.com/sabicalija/beamerthemetechnikum/releases/tag/v0.1.0
