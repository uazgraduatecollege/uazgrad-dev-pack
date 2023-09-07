# UArizona Grad College VS Code Extension Pack - README

## About

This extension pack installs:

- [Cucumber](https://marketplace.visualstudio.com/items?itemName=CucumberOpen.cucumber-official)
- [EditorConfig for VS Code](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)
- [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
- [Live Share](https://marketplace.visualstudio.com/items?itemName=MS-vsliveshare.vsliveshare)
- [PHP_CodeSniffer](https://marketplace.visualstudio.com/items?itemName=obliviousharmony.vscode-php-codesniffer)
- [Remote Development](https://marketplace.visualstudio.com/items?itemName=ms-vscode-remote.vscode-remote-extensionpack)
- [StandardJS](https://marketplace.visualstudio.com/items?itemName=standard.vscode-standard)

Not installed, but recommended:

- [Markdown PDF](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf)
- [VIM](https://marketplace.visualstudio.com/items?itemName=vscodevim.vim)

## Installation

1. Clone this repository locally. Checkout the most recent tag (recommended but optional).
2. Install the VS Code Extension Manager: `npm install --global vsce`
3. Generate the vsix package: `cd /path/to/uazgrad-dev-pack && vsce package`
4. Open VS Code -> Extensions and choose **Install from VSIX**

## Other Considerations

For CakePHP projects, we generally use the following PHP_CodeSniffer settings:

- PHP Code Sniffer Standard: `PSR12`
- PHP Code Sniffer-> Exec: Linux (or Osx): `./vendor/bin/phpcs`

**Enjoy!**

