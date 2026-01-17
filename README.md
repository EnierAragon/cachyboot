# CachyBoot

A custom Plymouth boot animation featuring a sleek tech aesthetic. Based on visual assets from @dripteck2 (TikTok).

## 🛠 Prerequisites

Ensure you have `plymouth` installed on your system. This theme was tested on **CachyOS (KDE Plasma/Wayland)** but should work on any Arch-based distribution.

## 📥 Installation

1. **Clone or download this repository.**
2. **Move the theme folder** to the Plymouth themes directory:\

```bash
sudo cp -r cachyboot /usr/share/plymouth/themes/
```
   
## 🚀 How to Apply
To set the theme and rebuild your initramfs (boot image), run:

```bash
sudo plymouth-set-default-theme -R cachyboot
```

Note: If you are using a non-Arch distro, you might need to run sudo update-initramfs -u or your specific system equivalent after setting the theme.

## 📜 License & Usage

Feel free to use, modify, and share this custom boot animation! 

The script is fully documented and designed to be easy to tweak. Whether you want to change the frame count, adjust the playback speed, or set your own loop points, you have total freedom to make it yours. 

If you create something cool based on this, I'd love to see it!

# Credits:

Visuals: @dripteck2 on TikTok.

Making: [EnierAragon]
