<div align="center">

# 🖼️ Linux Wallpapers Megapack

### A curated library of 1,300+ high-resolution wallpapers for Linux desktops.

Clean, deduplicated and optimized. Ready for **Hyprland**, **Sway**, **Caelestia Shell**, **GNOME**, **KDE** and any other setup.

[![Stars](https://img.shields.io/github/stars/gbarr3t0/wallpapers?style=flat-square&color=f6c177)](https://github.com/gbarr3t0/wallpapers/stargazers)
![Wallpapers](https://img.shields.io/badge/wallpapers-1300%2B-b4637a?style=flat-square)
![Resolution](https://img.shields.io/badge/resolution-1080p%20to%202K-31748f?style=flat-square)
![Size](https://img.shields.io/badge/size-~2.2%20GB-c4a7e7?style=flat-square)
![Use](https://img.shields.io/badge/use-non--commercial-9ccfd8?style=flat-square)

[Overview](#-overview) · [Highlights](#-highlights) · [Collection](#-collection) · [Installation](#-installation) · [Processing](#-how-the-collection-was-built) · [FAQ](#-faq) · [Credits](#-credits--original-sources) · [Takedown](#%EF%B8%8F-disclaimer--takedown-policy)

</div>

---

## 📖 Overview

**Linux Wallpapers Megapack** is a personal, hand-picked collection of desktop wallpapers, built for people who care about how their desktop looks and feels.

It brings together the best of several community wallpaper packs in one place, then goes a step further: every image was filtered, deduplicated and optimized, so you get a lean, consistent library instead of a pile of mismatched files.

The collection is compatible with any window manager or desktop environment, including **Hyprland, Sway, Caelestia Shell, GNOME and KDE**.

---

## 🌟 Highlights

- 🖥️ **Desktop-ready resolution:** every image is between Full HD (`1920x1080`) and 2K (`2560x1440`).
- 🧹 **Zero duplicates:** identical files were removed by comparing real file contents, not just names.
- 📐 **Landscape only:** vertical mobile crops were discarded.
- ⚡ **Lightweight:** optimized from **2.7 GB down to about 2.2 GB** without visible quality loss.
- 🎨 **Theme-friendly:** includes wallpapers matching popular palettes like Rosé Pine, Catppuccin, Nord, Gruvbox and Everforest.

---

## 🗂️ Collection

| Category | What you'll find |
|---|---|
| 🏡 **Cozy & Pixel Art** | Snowy biomes, voxel landscapes, rainy scenes, medieval fantasy and warm pixel art. |
| 🎨 **Color Palettes** | Wallpapers matching **Rosé Pine**, **Catppuccin**, **Nord**, **Gruvbox** and **Everforest**, so your desktop, terminal and wallpaper stay visually consistent. |
| 🎌 **Anime & Manga** | Stylized scenes, recolored manga panels and minimalist character art. |
| 🌌 **Landscapes & Minimal** | Nature photography, space, digital illustrations and clean vector art. |

### At a glance

| | |
|---|---|
| **Total wallpapers** | 1,300+ |
| **Resolution range** | `1920x1080` to `2560x1440` |
| **Formats** | PNG, JPG, WebP |
| **Collection size** | ~2.2 GB |
| **Orientation** | Landscape (desktop) |
| **Compatibility** | Any WM / DE |

---

## 🚀 Installation

Clone the entire collection straight into your wallpapers directory:

```bash
git clone --depth 1 https://github.com/gbarr3t0/wallpapers.git ~/wallpapers
```

> 💡 `--depth 1` downloads only the latest snapshot instead of the full Git history, saving time and disk space.

Once cloned, point your wallpaper manager of choice to the `~/wallpapers` folder and you're done.

---

## 🛠️ How the Collection Was Built

Every image went through the same pipeline, using standard open-source Linux command-line tools:

| Step | Goal | Tool |
|---|---|---|
| **1. Resolution filter** | Remove anything below Full HD (`1920x1080`) | ImageMagick (`identify`) + `find` / `awk` |
| **2. Deduplication** | Remove identical images that had different names across packs | `fdupes` |
| **3. Downscaling** | Resize only images larger than 2K to `2560x1440`; 1080p and 2K files were left untouched | ImageMagick (`mogrify`) |
| **4. Optimization** | Apply light, high-quality compression to cut file size | ImageMagick (`mogrify`) |
| **5. Batch processing** | Process everything in parallel across multiple CPU threads | `xargs` |

Result: the collection went from **2.7 GB to about 2.2 GB**.

---

## ❓ FAQ

<details>
<summary><b>Was the image quality reduced?</b></summary>
<br>

Not in any way you would notice on a desktop. Optimization was done with ImageMagick, a professional-grade command-line tool, using conservative settings. Lossless formats like PNG keep their full quality, and JPG/WebP files use a high quality level. Nothing was upscaled or heavily compressed.

</details>

<details>
<summary><b>Why is nothing above 2K?</b></summary>
<br>

Larger images were downscaled to `2560x1440`. A 4K+ source adds a lot of file size but brings no real benefit once your desktop scales it down, so capping at 2K keeps the collection light without sacrificing sharpness on typical monitors.

</details>

<details>
<summary><b>Why is nothing below Full HD?</b></summary>
<br>

Low-resolution images look blurry or pixelated on desktop monitors, so anything under `1920x1080` was removed.

</details>

<details>
<summary><b>Can I use these wallpapers commercially?</b></summary>
<br>

No. This repository is for **personal and non-commercial use only**. The artwork belongs to its original creators (see [Credits](#-credits--original-sources)).

</details>

---

## 🙏 Credits & Original Sources

This repository is a non-commercial compilation of work from great community collections on GitHub. All credit belongs to the original artists, creators and maintainers:

| Source | Contribution |
|---|---|
| **[rose-pine/wallpapers](https://github.com/rose-pine/wallpapers)** | Official Rosé Pine collection: voxel/Minecraft art by *neyfua*, manga recolors and photography. |
| **[D3Ext/aesthetic-wallpapers](https://github.com/D3Ext/aesthetic-wallpapers)** | Wide collection of aesthetic, minimal and Linux-themed wallpapers. |
| **[SleepyCatHey/CozyPixels](https://github.com/SleepyCatHey/CozyPixels)** | Cozy pixel art, Catppuccin, Nord and One Dark wallpapers. |
| **[mhkarimi1383/minecraft-wallpapers](https://github.com/mhkarimi1383/minecraft-wallpapers)** | Official Minecraft panoramas and biome wallpapers. |

Huge thanks to all of them for making their work available to the community. 💜

---

## ⚠️ Disclaimer & Takedown Policy

> **For personal and non-commercial use only.** I do not claim ownership of any artwork, photograph, or game/anime imagery in this repository.

Most images were collected from open community repositories where the original artist metadata was not always preserved.

**Are you the creator or copyright holder of an image here?**
Please [open an Issue](https://github.com/gbarr3t0/wallpapers/issues) and tell me which file is yours. I will either **add proper credit** or **remove it immediately**, whichever you prefer.

---

<div align="center">

**If this collection made your desktop look better, consider leaving a ⭐**
It helps other people find it!

</div>
