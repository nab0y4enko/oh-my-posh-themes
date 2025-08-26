# oh-my-posh-themes

A collection of custom themes for [oh-my-posh](https://github.com/JanDeDobbeleer/oh-my-posh), the cross-platform prompt theme engine for any shell.

## Overview

This repository contains personally crafted themes that enhance your terminal experience with beautiful, informative prompts. Built on the robust foundation of oh-my-posh, these themes provide excellent visual feedback while maintaining optimal performance.

## About

I created these themes using examples and inspiration from the official [oh-my-posh repository](https://github.com/JanDeDobbeleer/oh-my-posh), customizing them to provide a clean, informative, and visually appealing terminal experience.

## Themes

### agnoster-by-nab0y4enko.omp.json

A modern powerline-style theme inspired by the agnosterplus theme from the official oh-my-posh collection.

**Features:**
- 🕒 **Time display**: Shows current time in the right prompt (24-hour format)
- 👤 **User session**: Displays current user with clean white background
- 📁 **Smart path**: Agnoster-style path display with folder icons and separators
- 🌿 **Git integration**: Shows current branch with distinct styling
- ⚡ **Powerline symbols**: Uses beautiful Unicode symbols for seamless segment transitions
- 🎨 **Color coded**: Different background colors for easy visual distinction

**Color Scheme:**
- User session: White background with dark text
- Path: Light blue background for easy readability
- Git branch: Light green background indicating repository status
- Time: Blue text in right prompt

## Installation & Usage

### Remote Installation (Recommended)

You can use this theme remotely without downloading it locally. This method automatically fetches the latest version:

#### For Zsh (.zshrc)

```bash
eval "$(oh-my-posh init zsh --config 'https://raw.githubusercontent.com/nab0y4enko/oh-my-posh-themes/main/agnoster-by-nab0y4enko.omp.json')"
```

#### For other shells

Replace `zsh` with your shell name:

- **Bash**: `bash`
- **Fish**: `fish` 
- **PowerShell**: `pwsh`
- **Cmd**: `cmd`

Example for PowerShell:
```powershell
oh-my-posh init pwsh --config 'https://raw.githubusercontent.com/nab0y4enko/oh-my-posh-themes/main/agnoster-by-nab0y4enko.omp.json' | Invoke-Expression
```

### Local Installation

1. **Download the theme file:**
   ```bash
   curl -o ~/.config/oh-my-posh/agnoster-by-nab0y4enko.omp.json https://raw.githubusercontent.com/nab0y4enko/oh-my-posh-themes/main/agnoster-by-nab0y4enko.omp.json
   ```

2. **Add to your shell configuration:**
   ```bash
   eval "$(oh-my-posh init zsh --config ~/.config/oh-my-posh/agnoster-by-nab0y4enko.omp.json)"
   ```

### Prerequisites

#### Installing oh-my-posh

**macOS (Homebrew):**
```bash
brew install jandedobbeleer/oh-my-posh/oh-my-posh
```

**Other platforms:** See the [oh-my-posh installation guide](https://ohmyposh.dev/docs/installation)

#### Installing Fonts

A [Nerd Font](https://www.nerdfonts.com/) is required for proper symbol rendering.

**Install using oh-my-posh (recommended):**
```bash
oh-my-posh font install
```

**Recommended fonts:** FiraCode Nerd Font, JetBrains Mono Nerd Font, MesloLGM Nerd Font

#### Font Configuration

**Visual Studio Code:**
Add to your settings.json:
```json
{
  "terminal.integrated.fontFamily": "MesloLGM Nerd Font"
}
```

**macOS Terminal:**
```bash
# For Pro profile
osascript -e 'tell application "Terminal" to set font of settings set "Pro" to "MesloLGL Nerd Font Mono"'

# For Basic profile  
osascript -e 'tell application "Terminal" to set font of settings set "Basic" to "MesloLGL Nerd Font Mono"'
```

For more information on configuration, see the [oh-my-posh documentation](https://ohmyposh.dev/docs/configuration/general).

## Screenshots

*Screenshots will be added soon to showcase the theme in action.*

## Customization

The theme is designed to be easily customizable. You can modify the following aspects:

- **Colors**: Change the `background` and `foreground` properties in the JSON file
- **Symbols**: Update the `powerline_symbol`, `folder_icon`, or other icon properties
- **Time format**: Modify the `time_format` property (default: "15:04:05" for 24-hour format)
- **Path style**: Adjust the `style` property in the path segment

To customize, download the theme file locally and edit it according to your preferences.

## Contributing

Contributions are welcome! If you have suggestions for improvements or find any issues:

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## License

This project is open source. Feel free to use, modify, and distribute these themes.

## Support

If you encounter any issues or have questions:

- Check the [oh-my-posh documentation](https://ohmyposh.dev/docs/)
- Open an issue in this repository
- Make sure you have a compatible Nerd Font installed

---

**Enjoy your enhanced terminal experience!** 🚀