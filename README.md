# Marp template

This repository is a template for creating a presentation using [Marp](https://marp.app/). It includes a basic structure for a presentation, and a default theme written in [styles.css](styles.css). 

## Usage

1. Clone this repository
2. Edit the `slides.md` file to create your presentation
3. Preview the presentation by opening the `slides.md` file in Marp preview mode in Visual Studio Code (or any other solution that supports Marp, check the [Marp documentation](https://marp.app/) for more information)
4. Export the presentation to any format (PDF, HTML, etc.) using the Marp extension in Visual Studio Code

## Customization

In order to use your own theme, you can edit the `styles.css` file, and register it in the Marp themes in your Visual Studio Code settings:

```json
// Please put `.vscode/settings.json` on your workspace
{
    "markdown.marp.themes": [
        "https://example.com/foo/bar/custom-theme.css",
        "./themes/your-theme.css"
    ]
}
```

For more information about it, check [using custom CSS in Marp](https://marpit.marp.app/theme-css), and the [Visual Studio Code Marp extension documentation](https://github.com/marp-team/marp-vscode#use-custom-theme-css-shield).

