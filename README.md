# [Tokyo Night Ported Nvim](https://marketplace.visualstudio.com/items?itemName=Dionannd.tokyo-night-ported-nvim)

[![Preview in vscode.dev](https://img.shields.io/badge/preview%20in-vscode.dev-blue)](https://vscode.dev/theme/Dionannd.tokyo-night-ported-nvim)
[![Version](https://vsmarketplacebadges.dev/version/Dionannd.tokyo-night-ported-nvim.svg)](https://marketplace.visualstudio.com/items?itemName=Dionannd.tokyo-night-ported-nvim)

🏙 A clean, dark VSCode theme ported from Visual Studio Code & Nvim Tokyo Night theme, with support each language program.

### Screenshots

[font](https://philpl.gumroad.com/l/dank-mono) used in the image.

![Tokyo Night Ported Screenshoots](/images/screenshoots.png)

### Disable Italics

```json
"editor.tokenColorCustomizations": {
    "[Tokyo Night Ported Nvim]": {
        "textMateRules": [{
            "scope": [
                "comment",
                "meta.var.expr storage.type",
                "keyword.control.flow",
                "keyword.control.return",
                "storage.modifier"
            ],
            "settings": {
                "fontStyle": ""
            }
        }]
    }
}
```
