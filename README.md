# v0 README

This is VS Code language (grammar) support for internal v0 format of [Imparato](https://www.imparato.io)'s theatre plays.

(If you are not an Imparato developer or contributor, this grammar is of no interest to you, except to serve as VS Code grammar example.)


## Theme improvements

In order to improve display, you can add the following in your User Settings file (`$HOME/.vscode/settings.json` or `Preferences: Open User Settings`) :

```json
{
    "editor.tokenColorCustomizations": {
        "textMateRules": [{
            "scope": [
                "heading.section.v0"
            ],
            "settings": {
                "foreground": "#dd9977",
                "fontStyle": "bold"
            }
        }]
    }
}
```
