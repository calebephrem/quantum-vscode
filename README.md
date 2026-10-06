<br />
<div align="center">

  <img src="https://github.com/calebephrem/quantum-vscode/blob/main/assets/icon.png?raw=true" alt="Quantum Theme" width="200" height="200" />

  <p align="center" style="margin-top: 12px;">
    <strong><small>Quantum Theme for VS Code</small></strong>
  </p>
  
</div>

<table style="width:100%; table-layout: fixed; border-collapse: separate; border-spacing: 24px;">
  <tr>
    <td style="padding: 0; border: 0; vertical-align: top; min-width: 400px">
      <h4>Default</h4>
      <a href="https://github.com/calebephrem/quantum-vscode/blob/main/assets/themes/quantum.png?raw=true"><img src="https://github.com/calebephrem/quantum-vscode/blob/main/assets/themes/quantum.png?raw=true" /></a>
    </td>
    <td style="padding: 0; border: 0; vertical-align: top; min-width: 400px">
      <h4>Bordered</h4>
      <a href="https://github.com/calebephrem/quantum-vscode/blob/main/assets/themes/quantum-bordered.png?raw=true"><img src="https://github.com/calebephrem/quantum-vscode/blob/main/assets/themes/quantum-bordered.png?raw=true" /></a>
    </td>
    <td style="padding: 0; border: 0; vertical-align: top; min-width: 400px">
      <h4>Non-Italicized</h4>
      <a href="https://github.com/calebephrem/quantum-vscode/blob/main/assets/themes/quantum-non-italicized.png?raw=true"><img src="https://github.com/calebephrem/quantum-vscode/blob/main/assets/themes/quantum-non-italicized.png?raw=true" /></a>
    </td>
  </tr>
  <tr>
    <td style="padding: 0; border: 0; vertical-align: top; min-width: 400px">
      <h4>Dark</h4>
      <a href="https://github.com/calebephrem/quantum-vscode/blob/main/assets/themes/quantum-dark.png?raw=true"><img src="https://github.com/calebephrem/quantum-vscode/blob/main/assets/themes/quantum-dark.png?raw=true" /></a>
    </td>
    <td style="padding: 0; border: 0; vertical-align: top; min-width: 400px">
      <h4>Dark Bordered</h4>
      <a href="https://github.com/calebephrem/quantum-vscode/blob/main/assets/themes/quantum-dark-bordered.png?raw=true"><img src="https://github.com/calebephrem/quantum-vscode/blob/main/assets/themes/quantum-dark-bordered.png?raw=true" /></a>
    </td>
    <td style="padding: 0; border: 0; vertical-align: top; min-width: 400px">
      <h4>Dark Non-Italicized</h4>
      <a href="https://github.com/calebephrem/quantum-vscode/blob/main/assets/themes/quantum-dark-non-italicized.png?raw=true"><img src="https://github.com/calebephrem/quantum-vscode/blob/main/assets/themes/quantum-dark-non-italicized.png?raw=true" /></a>
    </td>
  </tr>
  <tr>
    <td style="padding: 0; border: 0; vertical-align: top; min-width: 400px">
      <h4>Mirage</h4>
      <a href="https://github.com/calebephrem/quantum-vscode/blob/main/assets/themes/quantum-mirage.png?raw=true"><img src="https://github.com/calebephrem/quantum-vscode/blob/main/assets/themes/quantum-mirage.png?raw=true" /></a>
    </td>
    <td style="padding: 0; border: 0; vertical-align: top; min-width: 400px">
      <h4>Mirage Bordered</h4>
      <a href="https://github.com/calebephrem/quantum-vscode/blob/main/assets/themes/quantum-mirage-bordered.png?raw=true"><img src="https://github.com/calebephrem/quantum-vscode/blob/main/assets/themes/quantum-mirage-bordered.png?raw=true" /></a>
    </td>
    <td style="padding: 0; border: 0; vertical-align: top; min-width: 400px">
      <h4>Mirage Non-Italicized</h4>
      <a href="https://github.com/calebephrem/quantum-vscode/blob/main/assets/themes/quantum-mirage-non-italicized.png?raw=true"><img src="https://github.com/calebephrem/quantum-vscode/blob/main/assets/themes/quantum-mirage-non-italicized.png?raw=true" /></a>
    </td>
  </tr>
</table>

## Installation

1. Open Extensions by clicking on the extension icon on the left sidebar panel in your VS Code
2. Search **Quantum Theme**
3. Install the one by _Caleb Ephrem_
4. Press `ctrl+shift+P` to expand the command palette (`cmd+shift+P` on mac)
5. Go under `Preferences: Color Theme`
6. Search for **Quantum**
7. Then click on **Quantum** (or other variants of it)
8. Give the [repo](https://github.com/calebephrem/quantum-vscode) a ⭐ star

🔥 Voilà! You have the the theme activated! ⚡

## Recommended Settings for Better Look

1. Open your command palette (`Ctrl+Shift+P`)
2. Search for `Preferences: Open User Settings (JSON)`
3. Edit the recommended settings into your `settings.json` file

> [!TIP]
> Optional settings are just optional, feel free to skip them if they’re not your style.

```jsonc
{
  // Theme
  "workbench.colorTheme": "Quantum", // or other variants of Quantum theme listed
  // download Fluent Icons extension
  "workbench.productIconTheme": "fluent-icons",
  // download Material Icon Theme extension
  "workbench.iconTheme": "material-icon-theme",
  "material-icon-theme.hidesExplorerArrows": true,
  "material-icon-theme.files.color": "#9fafaf",
  // Use #e0c060 instead of #40a0f0 for Windows-style folder colors
  "material-icon-theme.folders.color": "#40a0f0",

  // Appearance
  // Download and install the font for free from https://github.com/willfore/vscode_operator_mono_lig
  "editor.fontFamily": "Operator Mono Lig, Cascadia Code, JetBrains Mono, Fira Code, monospace",
  "editor.letterSpacing": 0.5, // don't add this if you are using vanilla monospace
  "editor.fontWeight": "normal",
  "editor.fontLigatures": true,
  "editor.glyphMargin": true,
  "editor.tabSize": 2, // 3 is also fine
  "editor.cursorStyle": "line",
  "editor.cursorBlinking": "expand",
  "editor.cursorSmoothCaretAnimation": "on",
  "editor.cursorWidth": 0, // 0 is default setting (default = 2), 3 is also fine
  "editor.guides.bracketPairs": false,
  "editor.wordWrap": "on",
  "breadcrumbs.enabled": false,
  "editor.hover.delay": 500,
  "files.trimTrailingWhitespace": true,
  "terminal.integrated.fontFamily": "JetBrains Mono, Operator Mono Lig, Cascadia Code, Fira Code, monospace",
  "terminal.integrated.cursorStyle": "line",
  "terminal.integrated.cursorWidth": 2,
  "terminal.integrated.fontLigatures.enabled": true,

  // Formatting
  // Download the Prettier extension if you haven't already
  "editor.defaultFormatter": "esbenp.prettier-vscode",

  // Remove or comment out all other color customizations and follow Quantum theme ;]
  "workbench.colorCustomizations": {},

  // Optional
  "editor.minimap.enabled": false,
}
```

> Again, you can download and install the _Operator Mono Lig_ font for free from https://github.com/willfore/vscode_operator_mono_lig.

## 📷 Screenshots

### CSS & SCSS

![css+scss](https://github.com/calebephrem/quantum-vscode/blob/main/assets/screenshots/css-scss.png?raw=true)

### Python & React

![python+react](https://github.com/calebephrem/quantum-vscode/blob/main/assets/screenshots/python-react.png?raw=true)

### HTML & Markdown

![html+markdown](https://github.com/calebephrem/quantum-vscode/blob/main/assets/screenshots/html-markdown.png?raw=true)

---

### License

Quantum theme is licensed under the MIT license.

### Final Notes

🧐 If you spot any funky colors, please don’t hesitate to [open an issue](https://github.com/calebephrem/quantum-vscode/issues).

If you’re enjoying the theme, show some love with:

- Giving the [repo](https://github.com/calebephrem/quantum-vscode) a ⭐ star
- Rating it 5 stars on the [VS Code Marketplace](https://marketplace.visualstudio.com/items?itemName=CalebEphrem.quantum)
- Drop a [review](https://marketplace.visualstudio.com/items?itemName=CalebEphrem.quantum&ssr=false#review-details) if you liked it!

Thanks a ton for the support, and happy coding! 😁
