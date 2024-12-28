# Gamesense Minimal Theme

**Gamesense Minimal** is a minimalistic light theme for code editors with a focus on readability and clean aesthetics. It features dark backgrounds combined with bright green highlights, ensuring great contrast and an easy-to-read experience for developers.

## Features

- **Minimal Design**: A simple yet effective color scheme, perfect for focusing on the code.
- **Green Highlights**: Key elements such as text, syntax, and UI elements are highlighted in a vibrant green.
- **Dark and Light Balance**: The background is dark enough to reduce eye strain, with subtle lighter accents.
- **Customizable**: Adjusts well to different coding environments, including various UI components like the editor, tabs, activity bar, and status bar.

## Installation

### For Visual Studio Code (VSCode)

1. Open Visual Studio Code.
2. Go to the Extensions view (`Ctrl+Shift+X`).
3. Search for "Gamesense Minimal" theme.
4. Install the theme from the Extensions marketplace.
5. Select the theme by going to `File` > `Preferences` > `Color Theme` and choose "Gamesense Minimal."

### Manual Installation

If you prefer to install manually, you can create a custom theme by adding the JSON code to your VSCode `settings.json` file:

1. Open the Command Palette (`Ctrl+Shift+P`).
2. Search for `Preferences: Open Settings (JSON)`.
3. Paste the theme JSON configuration under the `"workbench.colorCustomizations"` section.

Example:

```json
"workbench.colorCustomizations": {
    "editor.background": "#151514",
    "editor.foreground": "#95b806",
    "editor.selectionBackground": "#95b80633",
    "editor.lineHighlightBackground": "#95b80620",
    "editorCursor.foreground": "#95b806",
    // Add the rest of the colors here...
},
"editor.tokenColorCustomizations": {
    "textMateRules": [
        {
            "scope": ["comment"],
            "settings": {
                "foreground": "#a0a0a0",
                "fontStyle": "italic"
            }
        },
        {
            "scope": ["string"],
            "settings": {
                "foreground": "#95b806",
                "fontStyle": "bold"
            }
        },
        // Add the rest of the token colors here...
    ]
}
