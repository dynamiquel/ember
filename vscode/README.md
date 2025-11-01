# Ember Theme for VS Code

A warm, dark IDE theme that prioritises syntax clarity and avoids all cool colors.

## Installation

### Option 1: Install from Extension Development Host (For Testing)

1. Open the `vscode` folder in VS Code
2. Press `F5` to open a new Extension Development Host window
3. In the new window, open the Command Palette (`Cmd+Shift+P` on macOS or `Ctrl+Shift+P` on Windows/Linux)
4. Type "Preferences: Color Theme" and select it
5. Choose "Ember" from the theme list

### Option 2: Install Locally (For Personal Use)

1. Copy the entire `vscode` folder to your VS Code extensions directory:
   - **macOS**: `~/.vscode/extensions/ember`
   - **Windows**: `%USERPROFILE%\.vscode\extensions\ember`
   - **Linux**: `~/.vscode/extensions/ember`
2. Restart VS Code
3. Open the Command Palette (`Cmd+Shift+P` / `Ctrl+Shift+P`)
4. Type "Preferences: Color Theme" and select it
5. Choose "Ember" from the theme list

### Option 3: Package and Install (For Distribution)

1. Install `vsce` (VS Code Extension Manager):
   ```bash
   npm install -g @vscode/vsce
   ```
2. Navigate to the `vscode` folder:
   ```bash
   cd vscode
   ```
3. Package the extension:
   ```bash
   vsce package
   ```
4. Install the generated `.vsix` file:
   - Open VS Code
   - Go to Extensions view (`Cmd+Shift+X` / `Ctrl+Shift+X`)
   - Click the `...` menu and select "Install from VSIX..."
   - Select the generated `.vsix` file
5. Choose "Ember" from the theme picker

## Quick Theme Selection

- **Keyboard Shortcut**: `Cmd+K Cmd+T` (macOS) or `Ctrl+K Ctrl+T` (Windows/Linux)
- **Command Palette**: `Cmd+Shift+P` → "Preferences: Color Theme" → "Ember"

## Development

To test changes to the theme:

1. Make changes to `themes/Ember-color-theme.json`
2. Press `F5` to reload the Extension Development Host window
3. Changes are automatically applied

## Features

- Warm color palette (ambers, oranges, deep reds)
- High syntax clarity and contrast
- Comprehensive language support (JavaScript, TypeScript, CSS, HTML, Markdown, JSON, YAML, Docker, SQL, and more)
- Dark theme optimized for long coding sessions

## Files

- `package.json` - Extension manifest
- `themes/Ember-color-theme.json` - Theme definition file

**Enjoy!**
