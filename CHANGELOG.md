# Changelog

All notable changes to the Zarlo Frontend website will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- Initial CHANGELOG.md file to track project changes

## [0.2.0] - 2025-01-17

### Changed

- **MAJOR UI REDESIGN**: Complete redesign of hero section to match Lovable-style clean interface
- Updated hero title to "Build Websites Like a Wizard" with animated gradient on "Like a Wizard"
- Simplified subtitle to "Create apps and websites by chatting with AI"
- Replaced complex prompt interface with clean textarea input (3 sentences height)
- Changed submit button to "Create" with magic wand icon
- Removed hero badge, template cards, and stats sections for minimal design
- Updated input placeholder to "Ask Zarlo to create an internal tool that..."
- Improved button positioning with proper padding (15px from edges)
- Maintained all magical animations and gradient effects

### Removed

- Hero badge section
- Complex prompt interface container with tools and controls
- Creator template cards section  
- Stats section with revenue/time metrics
- Social proof section with avatars
- Quick start options buttons

### Technical Notes

- **REVERT POINT**: This version represents a clean, minimal Lovable-inspired interface
- All original magical styling and animations preserved
- Input field converted from input to textarea for multi-line support
- Button repositioned to bottom-right of textarea with proper spacing
- Responsive design maintained

## [0.1.0] - 2025-01-17

### Added

- Initial project setup
- Basic frontend structure
- Header component
- Routing configuration in App.jsx
- Initial pages setup

### Changed

- None

### Deprecated

- None

### Removed

- None

### Fixed

- None

### Security

- None

---

## How to use this changelog

When making changes to the website:

1. **Before making changes**: Note the current version and date
2. **After making changes**: Add a new entry under [Unreleased] with:
   - Date of change
   - Category (Added/Changed/Removed/Fixed)
   - Brief description of what was modified
3. **For major releases**: Move [Unreleased] items to a new version section

### Version Format

- MAJOR.MINOR.PATCH (e.g., 1.2.3)
- MAJOR: Incompatible changes or complete redesigns
- MINOR: New functionality added in a backward-compatible manner
- PATCH: Backward-compatible bug fixes or minor tweaks

### Reverting Changes

To revert to a previous version:

1. Check this changelog for the version you want
2. Use git log to find the corresponding commit
3. Create a new branch from that commit or revert specific changes
