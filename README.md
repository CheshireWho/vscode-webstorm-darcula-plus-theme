# Webstorm Darcula Plus Theme

Classic Webstorm Darcula Theme with small enhancements.

- The theme is based on <https://github.com/imekachi/webstorm-darcula/blob/master/themes/darcula-2022.json>.
- Small adjustments have been added to get it even closer to the original Darcula theme (e.g., some markdown adjustments and highlighting custom JSX tags differently than native HTML tags).
- Small enhancements have been added for features that were not highlighted in Webstorm (like types and interfaces, or the enclosing tags for interpolations in template literals).

## Installation

1. The VSIX file (i.e., the packaged extension) is available at the repository root. Download it.
2. In VSCode, go to the "Extensions" view and from there to "Views and More Actions" (that's the three dots icon at the top right side of the extensions sidebar) > "Install from VSIX...". Select the VSIX file. The theme extension is now being installed.
3. Go to "File" > "Preferences" > "Themes" > "Color Theme" and select the new theme.

## Development

The extension has been created following <https://code.visualstudio.com/api/extension-guides/color-theme#create-a-new-color-theme> and <https://code.visualstudio.com/api/get-started/your-first-extension>.
The generated [vsc-extension-quickstart.md](./vsc-extension-quickstart.md) has instructions on testing local changes.

To create a new package, run:

```bash
npx --package @vscode/vsce -- vsce package
```

More details on packaging: <https://code.visualstudio.com/api/working-with-extensions/publishing-extension#packaging-extensions>
