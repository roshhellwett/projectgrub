<!-- 🧩 GRUB THEME README — By Rosh Hellwett -->

<h1 align="center">✨ GRUB — VIMIX EDITION ✨</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Linux-2ea44f?style=for-the-badge&logo=linux&logoColor=white" />
  <img src="https://img.shields.io/badge/License-Apache%202.0-blue?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Resolution-1080p%20|%202K%20|%204K-orange?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Status-Stable-success?style=for-the-badge" />
</p>

---

<p align="center">
  <img src="https://github.com/roshhellwett/Grub/blob/9312833b24e2869e4d86d552e31f9ab7751aaf8b/template.jpg" width="700" alt="Grub Vimix Theme Preview"/>
</p>

<p align="center">
  <em>“Because even your bootloader deserves style.” 💻🖌️</em>
</p>

---

## 🌈 Overview

**GRUB — Vimix Edition** brings a **sleek, modern aesthetic** to your Linux bootloader.  
Inspired by the famous **Vimix** design language, this theme blends minimalism, contrast, and visual harmony to give your GRUB menu a professional and elegant touch.

---

## 🧩 Features

- 🎨 Clean and modern flat-design interface  
- 🖥️ Optimized for **1080p**, **2K**, and **4K** resolutions  
- 🧭 Easy plug-and-play setup  
- 🧡 Based on the **Vimix** color and typography scheme  
- ⚙️ Works across major Linux distributions (Ubuntu, Fedora, Arch, etc.)

---

## 🗂️ Files Included

| File | Description |
|------|--------------|
| `Vimix-1080p.zip` | Theme package for Full HD (1920×1080) |
| `Vimix-2k.zip` | Theme package for QHD (2560×1440) |
| `Vimix-4k.zip` | Theme package for UHD (3840×2160) |
| `LICENSE` | Apache License 2.0 |
| `README.md` | This file |

---

## ⚙️ Installation

### 🧰 Step 1 — Choose your version
Download your preferred resolution:
- [⬇️ Vimix-1080p.zip](./Vimix-1080p.zip)
- [⬇️ Vimix-2k.zip](./Vimix-2k.zip)
- [⬇️ Vimix-4k.zip](./Vimix-4k.zip)

### 📦 Step 2 — Extract the files
```bash
sudo mkdir -p /boot/grub/themes
sudo unzip Vimix-1080p.zip -d /boot/grub/themes/vimix
```
## 🧩 Apply the theme
Edit /etc/default/grub and add   :--   GRUB_THEME="/boot/grub/themes/vimix/theme.txt"

Then update GRUB:
```
sudo update-grub          # Debian / Ubuntu
# or
sudo grub2-mkconfig -o /boot/grub2/grub.cfg   # Fedora / RHEL
sudo reboot # Reboot System In End
```
---

© 2026 [Zenith Open Source Projects](https://zenithprojects.up.railway.app/). All Rights Reserved.  
Zenith is a Open Source Project Idea's by @roshhellwett

---
