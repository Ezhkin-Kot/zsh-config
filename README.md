# ZSH Config by Ezhkin-Kot

It's my own ZSH configuration for MacOS and the script for automatic installation of all these configurations, tools and dotfiles in your system. It was created for quickly setting up the system with one command. 

## Installation

### 1. Clone the repository

```sh
git clone https://github.com/Ezhkin-Kot/zsh-config.git
cd zsh-config
```

### 2. Run the install script
```sh
chmod +x ./install.sh
./install.sh
```

The script will:
- Install Homebrew if it’s not already installed
- Install Ghostty and iTerm2 terminal emulators
- Install useful CLI tools and plugins
- Set up oh-my-zsh, powerlevel10k, and custom configurations
- Configure git global environments from user's data
- Install original and Nerd JetBrains Mono fonts

### 3. Set up fonts

Set up JetBrains Mono Nerd font in iTerm preferences.

### 4. Restart your ZSH

After the installation is completed and the terminal opens, restart your shell with command:
```sh
source ~/.zshrc
```

## Installed Packages
- Ghostty - the best terminal emulator in my opinion.
- iTerm - another terminal emulator for MacOS only.
- `oh-my-zsh` – framework for managing Zsh configuration.
    - `zsh-vi-mode` - adds vim motions to your Zsh command line.
    - `zsh-autosuggestions` – suggests commands as you type, based on your history.
    - `zsh-syntax-highlighting` – adds syntax highlighting to your Zsh command line.
- `powerlevel10k` – a beautiful zsh theme configurator.
- `neovim` – the best code editor in the world. 
- `yazi` - a full-featured file manager in your terminal. 
- `zellij` – a terminal workspace and multiplexer, alternative to `tmux`, but does not require configuration.
- `zoxide` – a smarter `cd` command that remembers your most-used directories.
- `bat` – a `cat` clone with syntax highlighting and Git integration.
- `eza` – a modern replacement for `ls` with more features and better formatting.
- `fd` – a simple, fast alternative to `find`.
- `fzf` – a general-purpose command-line fuzzy finder.
- `gcc` – the GNU Compiler Collection for compiling C/C++ and other languages.
- `obfs4proxy` – a pluggable transport proxy for Tor.
- `openssl` – toolkit for TLS/SSL and cryptographic functions.
- `ripgrep` – a fast search tool like `grep`, optimized for large codebases.
- `thefuck` – corrects errors in previous console commands.
- `tldr` – simplified and community-driven man pages.
- `tmux` – a terminal multiplexer that lets you switch between sessions in one terminal window.
- `tor` – a tool for anonymous communication over the internet.
- `wget` – a command-line utility for downloading files from the web.

Fonts (included in fonts/)
- JetBrains Mono
- JetBrainsMono Nerd Font

## NeoVim

After all you also can install this NeoVim config:
https://github.com/Ezhkin-Kot/nvim

## Troubleshooting

If this zshrc config works incorrectly, you can restore your old config from `.zshrc-backup` using the following command:
```sh
cp ~/.zshrc-backup ~/.zshrc
```
