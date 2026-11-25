# Changelog

All notable changes to this theme are documented here.
The format follows [Keep a Changelog](https://keepachangelog.com/en/1.1.0/), versions follow [Semantic Versioning](https://semver.org/).

## [Unreleased]

### Changed
- Window, groups, separators and labels now use the greys and opacities measured on the current desktop release (neutral greys instead of the bluish phone greys): light window #f6f6f6 with white groups, dark window #1e1e1e with #282828 groups, separators black 10 % / white 12 %, labels 85 %.
- Desktop density: 13 px body text, 11 px small text, titles at 15 / 17 / 22 / 26 px.
- Switches in the desktop proportions (54 x 24 px in settings, 46 x 22 px in entity rows).
- Tile controls are capsules; with card-mod they are 32 px high instead of 42 px.
- States in system colours: covers, valves and media players blue, heating orange, cooling blue, motion orange.
- Filled buttons in the colour of selected content (#0064e1 / #0059d1), keyboard focus ring in the measured focus blue.
- card-mod: the selected sidebar entry is a neutral grey pill with label-coloured text and a blue symbol, as on the desktop, instead of a blue tint.

## [1.0.0] - 2026-11-24

### Added
- First release: one theme with light and dark mode.
- Flat content layer: cards as white (dark: dark grey) grouped lists with a hairline border on a neutral window. Works without add-ons.
- System colours; increased-contrast values where a default colour misses the WCAG minimum.
- Green switches with a white thumb, blue selection in the sidebar, blue keyboard focus ring, system UI font.
- Optional card-mod rules: floating glass sidebar with a light rim and rounded selection, hairline separators between rows of entities cards, compact section headings, system font in the sidebar.
