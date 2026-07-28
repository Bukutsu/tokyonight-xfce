# TokyoNight XFCE

A color-only XFCE style based on the Tokyo Night **night** palette.

The palette comes from [folke/tokyonight.nvim](https://github.com/folke/tokyonight.nvim). This is intentionally small: it changes GTK colors without replacing XFCE window decorations, icons, fonts, spacing, or layout.

## Install

```bash
mkdir -p ~/.local/share/themes
git clone https://github.com/Bukutsu/tokyonight-xfce.git /tmp/tokyonight-xfce
cp -r /tmp/tokyonight-xfce/TokyoNight ~/.local/share/themes/
```

Select `TokyoNight` in **Settings → Appearance → Style**.

Keep the normal XFCE window decorations in **Settings → Window Manager → Style**.

## Theme files

```text
TokyoNight/
├── gtk-2.0/gtkrc
├── gtk-3.0/gtk.css
├── xfwm4/                # Default XFCE geometry, recolored only
└── index.theme
```

## Palette

| Token | Color |
|---|---|
| Background | `#1a1b26` |
| Dark background | `#16161e` |
| Highlight | `#292e42` |
| Foreground | `#c0caf5` |
| Dim foreground | `#a9b1d6` |
| Gutter | `#3b4261` |
| Blue | `#7aa2f7` |
| Cyan | `#7dcfff` |
| Green | `#9ece6a` |
| Magenta | `#bb9af7` |
| Orange | `#ff9e64` |
| Red | `#f7768e` |
| Yellow | `#e0af68` |
| Comment | `#565f89` |
| Terminal black | `#414868` |

## Scope

This includes GTK2/GTK3 colors and an XFWM4 theme made by recoloring the stock XFCE `Default` XPM assets. Window decoration dimensions, button layout, spacing, and other geometry remain from the default theme. It does not include an icon theme, wallpaper, panel layout, or application configuration.
