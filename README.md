# Omarchy Dotfiles Backup

A backup of my customized Omarchy configuration files for Hyprland.

## 📁 Included Files

The `dot_files_backup/` directory contains:

- `monitors.lua` — Monitor layout, resolution, scaling, positioning, and refresh rate.
- `looknfeel.lua` — Hyprland appearance, gaps, borders, rounding, animations, and other visual settings.
- `hyprsunset.conf` — Hyprsunset configuration.

## 🔄 Restore Configuration

You **don't need to clone this repository**.

Run this single command in your terminal:

```bash
curl -fsSL https://raw.githubusercontent.com/noah8282/omarchy_dot_files/main/dot_files_backup/monitors.lua -o ~/.config/hypr/monitors.lua && curl -fsSL https://raw.githubusercontent.com/noah8282/omarchy_dot_files/main/dot_files_backup/looknfeel.lua -o ~/.config/hypr/looknfeel.lua && curl -fsSL https://raw.githubusercontent.com/noah8282/omarchy_dot_files/main/dot_files_backup/hyprsunset.conf -o ~/.config/hypr/hyprsunset.conf
```

This will download and replace all three configuration files automatically.

### ⚠️ Warning

This command **overwrites your existing configuration files**.

If you have customized these files, back them up before running the command.

## 📌 Installed Location

The files will be installed to:

```text
~/.config/hypr/
├── monitors.lua
├── looknfeel.lua
└── hyprsunset.conf
```

## 🔄 Apply Changes

After restoring the files, reload Hyprland:

```bash
hyprctl reload
```

If the changes don't fully apply, log out and log back in.

## 💾 Purpose

This repository is a personal backup of my Omarchy configuration.

It provides a quick way to restore my preferred:

- 🖥️ Monitor configuration
- 🎨 Hyprland appearance
- 🌙 Hyprsunset settings

on another Omarchy installation.