# Secrets

Storage for workstation device secrets.  Powered with chezmoi.

## Prerequsites
- Chezmoi and git available in your shell.  With nix you can open a nix shell with these via `nix-shell -p chezmoi git`
- Your super secret key installed inside `~/.age` with the name `personal-key.txt`

## Installation
1. Pull the repo via chezmoi: `chezmoi init https://github.com/fred-drake/dotfiles.git`
2. Apply the changes `chezmoi apply`
