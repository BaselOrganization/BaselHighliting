# Basel - Syntax Highlighting

Syntax highlighting extension for the Basel programming language in Visual Studio Code.

## Features

- **Syntax Highlighting**: Full syntax highlighting for `.bs` files
- **Language Support**: Supports the Basel programming language
- **Colorization**: Keywords, strings, comments, and other syntax elements are colorized

## Installation

1. Open VS Code
2. Press `Ctrl+Shift+X` (Windows/Linux) or `Cmd+Shift+X` (macOS) to open Extensions
3. Search for "Basel"
4. Click Install

Or install from a VSIX file:
1. Run `vsce package` to generate the VSIX
2. Press `Ctrl+Shift+P` and run "Extensions: Install from VSIX"

## Usage

Open any file with `.bs` extension to see the syntax highlighting:

```basel
// Example Basel code
function hello() {
    print("Hello, World!");
}
```

## File Association

Files with `.bs` extension are automatically recognized and highlighted.

## Requirements

- Visual Studio Code 1.109.0 or higher

## Extension Settings

This extension doesn't add any VS Code settings.

## Known Issues

No known issues.

## Release Notes

### 0.0.1

Initial release of Basel syntax highlighting.

## Contributing

If you find any issues or have suggestions, please open an issue on the repository.

**Enjoy!**
