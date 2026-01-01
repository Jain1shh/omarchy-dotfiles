# Omarchy Dotfiles

Personal dotfiles that work **on top of Omarchy defaults**.

This repository contains **only user overrides**, not a full Omarchy or Hyprland configuration.

## What’s included
- Hyprland override configs
- Waybar config (JSONC only)

Omarchy defaults, themes, and generated files are intentionally excluded as they may get modified through system updates.

## How to use on a new installation

1. Install Omarchy and log in once
2. Clone this repository
3. Copy the configs into `~/.config`

```bash
```
```bash
git clone <repo-url>
cp -r omarchy-dotfiles/hypr ~/.config/
cp -r omarchy-dotfiles/waybar ~/.config/

4. Log out and log back in to apply all changes
