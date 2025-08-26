# oh-my-posh-themes

A collection of custom themes for [oh-my-posh](https://github.com/JanDeDobbeleer/oh-my-posh), the cross-platform prompt theme engine for any shell.

## Overview

This repository contains personally crafted themes that enhance your terminal experience with beautiful, informative prompts. Built on the robust foundation of oh-my-posh, these themes provide excellent visual feedback while maintaining optimal performance.

## About

I created these themes using examples and inspiration from the official [oh-my-posh repository](https://github.com/JanDeDobbeleer/oh-my-posh), customizing them to provide a clean, informative, and visually appealing terminal experience.

## Installation & Usage

### Remote Installation (Recommended)

You can use this theme remotely without downloading it locally. This method automatically fetches the latest version:

#### For Zsh (.zshrc)

```bash
eval "$(oh-my-posh init zsh --config 'https://raw.githubusercontent.com/nab0y4enko/oh-my-posh-themes/main/agnoster-by-nab0y4enko.omp.json')"
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

**Recommended fonts:** MesloLGM Nerd Font, FiraCode Nerd Font, JetBrains Mono Nerd Font

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