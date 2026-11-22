<div align="center">

# 🖼️ Linux Wallpapers Megapack

**1,300+ curated high-resolution wallpapers for your Linux desktop.**

Optimized for Hyprland, Sway, Caelestia Shell, GNOME, KDE and any other setup you're ricing.

![Wallpapers](https://img.shields.io/badge/wallpapers-1300%2B-b4637a?style=flat-square)
![Resolution](https://img.shields.io/badge/resolution-1920x1080%2B-31748f?style=flat-square)
![Use](https://img.shields.io/badge/use-non--commercial-9ccfd8?style=flat-square)

</div>

---

## 📖 About

Linux Wallpapers Megapack is a personal, hand-picked collection of desktop wallpapers built for people who care about how their desktop looks and feels.

Every image went through a cleanup pipeline:

- **Resolution filter:** only images at `1920x1080` or above were kept.
- **Orientation filter:** vertical mobile crops were removed.
- **Deduplication:** exact duplicates were detected and deleted.
- **Optimization:** files were compressed for fast loading, without visible quality loss.

The result is a clean, ready-to-use library, with no filler and no wallpapers that look bad on a desktop monitor.

---

## ✨ Categories & Themes

| Category | What you'll find |
|---|---|
| 🏡 **Cozy & Pixel Art** | Snowy biomes, voxel landscapes, rainy scenes, medieval fantasy and warm pixel art. |
| 🎨 **Color Palettes** | Wallpapers matching **Rosé Pine**, **Catppuccin**, **Nord**, **Gruvbox** and **Everforest**, so your desktop, terminal and wallpaper stay consistent. |
| 🎌 **Anime & Manga** | Stylized scenes, recolored manga panels and minimalist character art. |
| 🌌 **Landscapes & Minimal** | Nature photography, space, digital illustrations and clean vector art. |

---

## 🚀 Quick Start

Clone the whole collection straight into your wallpapers directory:

```bash
git clone --depth 1 https://github.com/gbarr3t0/wallpapers.git ~/wallpapers
```

> 💡 `--depth 1` downloads only the latest snapshot, which saves time and disk space.

### Setting a wallpaper

```bash
# swww
swww img ~/wallpapers/your-image.png

# Sway (add to your config)
output * bg ~/wallpapers/your-image.png fill

# GNOME
gsettings set org.gnome.desktop.background picture-uri-dark "file://$HOME/wallpapers/your-image.png"
```

### Pick a random wallpaper

```bash
find ~/wallpapers -type f \( -iname '*.png' -o -iname '*.jpg' -o -iname '*.jpeg' \) | shuf -n 1
```

---

## 🙏 Credits & Original Sources

This repository is a non-commercial compilation of work from great community collections on GitHub. All credit belongs to the original artists, creators and maintainers:

- **[rose-pine/wallpapers](https://github.com/rose-pine/wallpapers)**: official Rosé Pine collection (voxel/Minecraft art by *neyfua*, manga recolors and photography).
- **[D3Ext/aesthetic-wallpapers](https://github.com/D3Ext/aesthetic-wallpapers)**: wide collection of aesthetic, minimal and Linux-themed wallpapers.
- **[SleepyCatHey/CozyPixels](https://github.com/SleepyCatHey/CozyPixels)**: cozy pixel art, Catppuccin, Nord and One Dark wallpapers.
- **[mhkarimi1383/minecraft-wallpapers](https://github.com/mhkarimi1383/minecraft-wallpapers)**: official Minecraft panoramas and biome wallpapers.

---

## ⚠️ Disclaimer & Takedown Policy

> **For personal and non-commercial use only.** I do not claim ownership of any artwork, photograph, or game/anime imagery in this repository.

Most images were collected from open community repositories where the original artist metadata was not always preserved.

**Are you the creator or copyright holder of an image here?**
Please [open an Issue](../../issues) and tell me which file is yours. I will either **add proper credit** or **remove it immediately**, whichever you prefer.

---

<div align="center">

If this collection made your desktop look better, consider leaving a ⭐ on the repo. It helps others find it!

</div>
