# Changelog

All notable changes to this project will be documented in this file.

## [2.0.1] - 2026-01-14

### Changed

- **BREAKING**: CLI command changed from `rendermd` to `mdvp`
- Configuration file renamed from `.rendermdrc` to `.mdvprc`
- Updated package.json repository URLs to point to new GitHub repository

### Migration Guide

Users of v2.0.0 should:

1. Update your aliases or scripts to use `mdvp` instead of `rendermd`
2. Rename config files: `.rendermdrc` → `.mdvprc` (optional, both work for now)
3. Install the new version: `npm install -g md-viewport@latest`

## [2.0.0] - 2026-01-14

### Changed

- **BREAKING**: Package renamed from `@showwaiyan/rendermd` to `md-viewport`
- **BREAKING**: GitHub repository moved to https://github.com/Showwaiyan/md-viewport
- CLI command remains `rendermd` (changed to `mdvp` in v2.0.1)
- Updated all documentation to reflect new package name and repository URL

### Migration Guide

Users of `@showwaiyan/rendermd` should:

1. Uninstall old package: `npm uninstall -g @showwaiyan/rendermd`
2. Install new package: `npm install -g md-viewport`
3. CLI usage: `mdvp file.md` (changed from `rendermd` in v2.0.1)

## [1.0.2] - 2026-01-14

### Fixed

- CLI version now reads from package.json dynamically
- Updated TypeScript target to ES2022 for top-level await support

## [1.0.1] - 2026-01-14

### Changed

- Updated documentation to reflect scoped package name `@showwaiyan/rendermd`
- Added npm badges to README
- Added npx usage instructions
- Updated all installation commands in documentation

## [1.0.0] - 2026-01-14

### Added

- Initial release
- GitHub Flavored Markdown support
- Syntax highlighting with Highlight.js
- Math rendering with KaTeX
- Mermaid diagram support
- Auto-generated table of contents
- Copy code button functionality
- GitHub Modern styling with light/dark mode
- Configuration file support (.rendermdrc)
- CLI with comprehensive options
- Auto-cleanup of temporary files
- Cross-platform browser opening
