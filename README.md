<div align="center">
  <h1>roottool's dotfiles</h1>
  <img alt="Sample" src="https://user-images.githubusercontent.com/11808736/146920735-d30c270e-992f-441f-82cf-9dfdce51f613.png"/>
</div>

## ℹ️ Overview

This dotfiles repository is intended to be used for Linux distributions under WSL2.

## 🖥️ My environment

- Windows 11
- WSL2
  - Debian Bullseye

## ⚙️ Components

- Linuxbrew
- starship
- zinit

## 🔰 How to use

1. Clone this repository
2. Move to the cloned repository
3. Execute the command
    ```bash
    make install
    ```
4. Create `~/.gitconfig_local`

   Example
    ```
    [user]
      name = sample
      email = sample@example.com
      signingkey = THIS15EXAMPLE
    ```
5. Create `~/local.zsh`

   Example
    ```zsh
    # BROWSER
    export BROWSER='Your browser execution file path'

    # PATH
    export WINDOWS_VSCODE='Your VS Code folder path within Windows'
    export PATH=$WINDOWS_VSCODE/bin:$PATH
    ```
6. Reboot your distribution
