# Karvulas Evergreen Theme

An evergreen-inspired light theme for Visual Studio Code with dedicated language palettes.

Available theme:

- **Karvulas Evergreen Light:** White and soft slate surfaces, evergreen accents, and colorful syntax tuned for a light editor

## Highlights

- Coordinated editor, panel, sidebar, and Activity Bar surfaces
- Evergreen accents with soft borders, separators, and selection states
- Matching menus, notifications, hovers, IntelliSense, and Command Palette
- A custom terminal ANSI palette for the light theme
- Markdown Preview styles for headings and syntax-highlighted code blocks

## Language Support

Karvulas Evergreen Light uses dedicated syntax palettes for individual languages. These palettes apply to source editors; the rendered Markdown Preview has its own heading and code colors.

- **Avalonia XAML (AXAML):** Blue elements, green attributes, purple namespaces and punctuation, cyan values, and slate comments
- **XML:** Coordinated colors for elements, attributes, namespaces, values, entities, declarations, comments, and CDATA
- **C#:** Green directives and class names, blue modifiers, control keywords, and methods, purple punctuation, cyan strings, and gold numbers
- **Rust:** Green declarations, including `static`, and type names; purple modifiers; blue control keywords, functions, macros, lifetimes, and punctuation; cyan strings; and gold primitive types, numbers, and booleans, with matching rust-analyzer semantic colors
- **Python:** Purple imports, declarations, and classes; blue control keywords; green modules and functions; cyan strings; and gold built-in types, numbers, and language constants
- **JavaScript:** Green module and variable declarations, blue control keywords and modifiers, purple functions, cyan strings, and gold numbers and booleans
- **TypeScript / TSX:** JavaScript-coordinated colors for types, interfaces, enums, decorators, and JSX elements and attributes
- **HTML:** Blue elements, green attributes, cyan values, purple punctuation and entities, gold doctype declarations, and slate comments
- **CSS:** Green properties and class selectors, blue element and ID selectors, purple functions and pseudo selectors, cyan colors and strings, and gold numbers
- **JSON / JSONC:** Green keys, cyan strings, gold numbers, purple constants and punctuation, with slate comments in JSONC
- **TOML:** Green keys, blue table names, cyan strings, gold numbers, booleans, and dates, purple punctuation, and slate comments, with matching Taplo semantic key colors
- **CSV:** Five repeating column colors for comma-separated files, with each first-row header matching its column's values
- **Markdown:** Graduated green headings, green heading and list markers, colored emphasis, gold inline code, blue links, and green table pipes
- **Other languages:** Quoted strings use the shared cyan color; other text uses the theme's base colors until a dedicated palette is added

TOML syntax highlighting is included for `.toml`, `Cargo.lock`, and `uv.lock` files. **Even Better TOML** (Taplo) is optional for validation, completion, and formatting; its semantic key colors also match the theme.

## Installation

1. Open the **Extensions** view in Visual Studio Code.
2. Search the Visual Studio Marketplace for **Karvulas Evergreen Theme** by **Karvulas**.
3. Select **Install**.
4. Open **Preferences: Color Theme** and choose **Karvulas Evergreen Light**.

## Feedback

Found an issue or have a suggestion? Open an issue on the [GitHub repository](https://github.com/emrakbult/karvulas-evergreen-theme/issues).

## License

Karvulas Evergreen Theme is available under the [MIT License](LICENSE).

The bundled TOML grammar is from Taplo; see [third-party notices](THIRD_PARTY_NOTICES.md).
