# Changelog

## Unreleased

## 0.6.1 - 2026-10-08

### Changed

- Colored C# method names blue in both TextMate and Roslyn semantic highlighting, including extension methods.

## 0.6.0 - 2026-10-07

### Added

- Added a dedicated Rust palette for declarations, types, functions, macros, lifetimes, literals, attributes, comments, and punctuation, with matching rust-analyzer semantic colors.
- Added a dedicated TOML palette for keys, tables, strings, numbers, booleans, dates, comments, and punctuation, with matching Taplo semantic key colors.
- Added a Rust grammar injection to distinguish green `static` declarations from purple modifiers, while coloring control keywords blue.
- Bundled TOML language detection, syntax grammar, comment toggling, and bracket/quote pairs for `.toml`, `Cargo.lock`, and `uv.lock` files, so basic highlighting works without a separate language extension.

## 0.5.1 - 2026-10-01

### Changed

- Rebalanced Python colors with purple imports, declarations, and classes, plus green modules and functions.

## 0.5.0 - 2026-09-30

### Added

- Added CSV language detection and five repeating column colors, with matching colors for first-row headers and values.
- Colored CSV field separators purple while keeping commas inside quoted fields in the field color.

## 0.4.2 - 2026-09-28

### Added

- Added a 128×128 PNG extension icon for VS Code and the Visual Studio Marketplace.

## 0.4.1 - 2026-09-27

### Fixed

- Colored TypeScript and TSX `async` modifiers and control keywords such as `if` and `return` with the intended blue palette.

### Changed

- Colored Markdown heading markers, emphasis markers, list markers, and table pipes with the main green accent.

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
