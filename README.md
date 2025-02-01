# VS Code Extension for WowLang Syntax Highlighting

This is a VS Code extension that provides syntax highlighting support for WowLang files.

## Features

- Syntax highlighting for `.wow` files
- Support for WowLang keywords and constructs
- Easy-to-use and lightweight

## Installation

### From VS Code Marketplace
1. Open the extension marketplace in VS Code (Ctrl+Shift+X or Cmd+Shift+X)
2. Search for "WowLang"
3. Click "Install"
4. Reload VS Code

### Manual Installation
1. Download the `.vsix` file from the [releases page](https://github.com/beachio/wowlang-vscode/releases)
2. Open VS Code
3. Press Ctrl+Shift+P (Cmd+Shift+P on macOS)
4. Type "Install from VSIX" and select it
5. Choose the downloaded `.vsix` file
6. Reload VS Code

## Usage

1. Open a file with the `.wow` extension
2. The syntax highlighting will be automatically applied
3. You can also manually set the language mode to "WowLang" for any file:
   - Click on the language selector in the bottom-right corner
   - Search for "WowLang"
   - Select it to apply syntax highlighting

## Development

### Prerequisites
- Node.js (v14 or higher)
- npm (v6 or higher)
- VS Code

### Setup
1. Clone the repository
   ```bash
   git clone https://github.com/beachio/wowlang-vscode.git
   cd wowlang-extension
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Open in VS Code
   ```bash
   code .
   ```

### Testing the Extension
1. Press F5 to open a new window with your extension loaded
2. Create a new file with a `.wow` extension
3. Verify that syntax highlighting works as expected

### Packaging the Extension
1. Install vsce (VS Code Extension Manager)
   ```bash
   npm install -g vsce
   ```

2. Package the extension
   ```bash
   vsce package
   ```
   This will create a `.vsix` file in your project directory.

## Contributing

1. Fork the repository
2. Create a new branch for your feature
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes
4. Test your changes
5. Commit your changes
   ```bash
   git commit -m "Add your commit message"
   ```
6. Push to your fork
   ```bash
   git push origin feature/your-feature-name
   ```
7. Submit a pull request

## Uninstalling

1. Open the extension marketplace in VS Code
2. Search for "WowLang"
3. Click "Uninstall"
4. Reload VS Code

## Updating

1. Open the extension marketplace in VS Code
2. Search for "WowLang"
3. Click "Update"
4. Reload VS Code

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

If you encounter any issues or have suggestions, please file them in the [GitHub issues](https://github.com/beachio/wowlang-vscode/issues) section.

