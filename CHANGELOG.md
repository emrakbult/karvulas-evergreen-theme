# Changelog

## Unreleased

## 0.4.0 - 2026-09-27

### Added

- Added dedicated Python syntax and semantic colors for imports, declarations, types, functions, literals, and punctuation.
- Added JavaScript and TypeScript/TSX palettes for declarations, classes, types, functions, properties, literals, and JSX.
- Added HTML colors for tags, attributes, values, entities, declarations, and comments.
- Added CSS colors for selectors, properties, values, functions, at-rules, colors, and units.

### Changed

- Refined C# token categories and semantic colors, including gold boolean literals to match the `bool` keyword.
- Narrowed JavaScript and TypeScript method coloring to function names and distinguished getter and setter keywords from property names.
- Aligned common JavaScript and TypeScript variable declarations with the green C# declaration palette.
- Clarified syntax rule names across the existing language palettes.
- Made the chat request bubble backgrounds and find-in-selection border translucent while preserving their appearance on white surfaces.
- Updated the README installation steps for Visual Studio Marketplace distribution.

## 0.3.0 - 2026-09-26

### Added

- Added targeted C# TextMate rules for modifiers, type keywords, references, and control keywords.
- Added punctuation rules for AXAML, XML, JSON/JSONC, and Markdown, plus a shared cyan fallback for quoted strings.
- Added green text selection styling to Markdown Preview.

### Changed

- Refined the existing AXAML, XML, C#, and JSON/JSONC palettes with coordinated green, blue, purple, cyan, and gold syntax colors.
- Harmonized Evergreen accents across the workbench, terminal ANSI palette, and Markdown Preview code highlighting.
- Smoothed the green gradient for Markdown headings in both the editor and Preview.
- Refined list selection colors with dark text on active items, green text on inactive selections, and green focus outlines.
- Expanded the README with theme highlights, current language palettes, installation guidance, and feedback information.

## 0.2.0 - 2026-09-25

### Added

- Introduced the Karvulas Evergreen Light palette with neutral workbench surfaces and green accents.
- Added dedicated JSON, JSONC, and Markdown source-editor colors, including a graduated green scale for Markdown headings.
- Added Markdown Preview styles for Evergreen Light headings and code highlighting.

### Changed

- Aligned the extension, Light theme file, launch configurations, and repository metadata with the Evergreen name.
- Removed the empty Dark theme contribution until that variant is ready.
- Refined Light theme selection, Activity Bar, Explorer, and code-block colors.
- Restored the launch configuration format version to `0.2.0`.
