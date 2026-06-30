# Changelog

## v2.0.0

### Added

- Added separate branches for version management:
  - `main` for latest Acode versions
  - `legacy` for older Acode versions

### Changed

- Refactored plugin architecture for compatibility with newer Acode versions
- Updated trigger system from `| + Enter` to `Ctrl + Alt + H`
- Updated README and documentation
- Improved initialization flow for modern Acode environments

### Fixed

- Fixed compatibility issues with Acode v1.12.6 (1001)
- Fixed `Cannot read properties of undefined (reading 'addEventListener')`
- Fixed plugin loading issues on newer Acode versions

## v1.0.1

- Added author URL and GitHub profile in plugin metadata
- Updated readme with support links and improved documentation
- Fixed several bugs
- Changed plugin price to free

## v1.0.0

- Initial release
- Trigger `|` + `Enter` to expand HSL `:root` snippet
- 7 color presets — Purple, Blue, Pink, Green, Cyan, Orange, Red
- Dark & Light mode support
- Cursor auto-jumps to `--hue` after insert
