# VS Code Customizer 🎨

A collection of beautiful and customizable themes for Visual Studio Code that enhance your coding experience. This repository contains carefully crafted color schemes and settings to make your VS Code environment both aesthetically pleasing and functional.

## Available Themes

### 1. Modern Dark Theme

A sleek dark theme with vibrant syntax highlighting and a modern look.

- Custom syntax highlighting with fresh colors
- Dark background with neon accents
- Optimized for readability
- Perfect for long coding sessions

### 2. Eco Theme 🌲

A nature-inspired theme that brings the outdoors to your code editor.

- Forest greens and lake blues
- Nature-inspired syntax highlighting
- Warm oak accents
- Easy on the eyes

## Features

- Custom syntax highlighting
- Carefully selected color combinations
- Enhanced UI elements
- Optimized sidebar and activity bar
- Beautiful line numbers and cursor
- Custom git decoration colors

## Installation

### Step 1: Get the Files

Clone this repository:

```bash
git clone https://github.com/lakipop/VScode-Customizer.git
```

### Step 2: Install Required Extension

1. Install the "Custom CSS and JS Loader" extension
2. Extension ID: `be5invis.vscode-custom-css`
3. Install from the [Custom CSS and JS Loader extension page](https://marketplace.visualstudio.com/items?itemName=be5invis.vscode-custom-css)

### Step 3: Setup Theme Files

1. Create a permanent folder for themes (e.g., `VSThemes` in your Documents)
2. Copy the contents of the `themes` folder to your chosen location
3. Note down the full path to your theme folder

### Step 4: Configure VS Code

1. Open VS Code Settings:
   - Press `Ctrl+,` (Windows/Linux) or `Cmd+,` (macOS)
   - Click the "Open Settings (JSON)" icon in the top-right corner

2. Add these settings to your `settings.json`:

   ```jsonc
   {
     "workbench.colorTheme": "Vivid Black",
     "vscode_custom_css.imports": [
       "file:///C:/Users/YourUsername/Documents/VSThemes/Color.css"  // Update this path!
     ]
   }
   ```

3. Update the path in `vscode_custom_css.imports`:
   - Use your actual theme file path
   - Use forward slashes (/) not backslashes
   - Include `file:///` prefix
   - Windows example: `file:///C:/Users/Username/Documents/VSThemes/Color.css`
   - macOS/Linux example: `file:///home/username/Documents/VSThemes/Color.css`

### Step 5: Enable the Theme

1. Open Command Palette (`Ctrl+Shift+P` or `Cmd+Shift+P`)
2. Type "Enable Custom CSS and JS"
3. Select and run the command
4. Click "Restart" when prompted

### Troubleshooting

If the theme doesn't appear:

- Verify file paths in `settings.json` are correct
- Run VS Code as administrator once
- Try the "Enable Custom CSS and JS" command again
- Reload VS Code window
- Check extension is properly installed
- Ensure no syntax errors in settings.json

For any issues, please check the [issues page](https://github.com/lakipop/VScode-Customizer/issues) or create a new one.

1. Applying themes:

   - The theme colors will be automatically applied
   - If colors don't update immediately, try:
     - Reload VS Code window (`Ctrl+Shift+P` or `Cmd+Shift+P`, then type "Reload Window")
     - Or restart VS Code completely

2. Troubleshooting:

   - Make sure all file paths in `settings.json` match your actual file locations
   - Check that the theme files are properly copied to your `.vscode` folder
   - Verify there are no syntax errors in your `settings.json`

## Preview

(Coming soon: Theme preview screenshots)

## Customization

You can customize these themes further by modifying:

- `settings.json`: General VS Code settings and UI colors
- `Color.css`: Main syntax highlighting colors
- `Ecotheme.css`: Nature-inspired theme colors

## Upcoming Features

Stay tuned for:

- More theme variations
- Light theme versions
- Custom icon packs
- Additional language-specific highlighting
- Theme generator tool

## Contributing

Feel free to contribute to this project by:

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a new Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Support

If you like this theme collection, don't forget to give it a star ⭐️

---

Created with 💚 by [lakipop](https://github.com/lakipop)
