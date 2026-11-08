# AGENTS.md

Contributor guidance for the CyberPhunk Omarchy desktop theme.

## Scope

This repository contains theme data and artwork for Omarchy. Keep it free of executable installers, plugins, hooks, widgets, build tooling and other bundled code. Put separate tools in their own repositories.

## Theme files

- `colors.toml` is the desktop palette source.
- `hyprland.conf` provides the active-window border styling.
- `backgrounds/` contains compressed WebP wallpaper artwork.
- `preview.png`, `preview-unlock.png` and `unlock.png` are theme artwork.
- `icons.theme` and `lazygit.yml` are optional preference/configuration files.

Keep gallery artwork representative of the actual desktop theme. Do not include personal information in screenshots.

## Editing and validation

Prefer editing source artwork and palette files rather than hand-editing rendered screenshots. Check changed image dimensions, format and size. Review the complete diff and ensure no executable code or build/install tooling has been introduced.
