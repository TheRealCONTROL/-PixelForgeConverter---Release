# PixelForge Converter v2.2

<p align="center">
  <img src="https://i.ibb.co/hJ1Y8scX/8b2c08db7688.png" width="100%">
</p>

<p align="center">
A modern image conversion tool built with <b>Python (PySide6)</b>, featuring a clean Steam-inspired interface.
</p>

PixelForge Converter is an all-in-one image conversion utility that supports batch image conversion, GIF frame extraction, video-to-GIF conversion, and full DDS compression (BC1 / BC3 / BC5) without requiring external DDS tools.

---

# ✨ Highlights

- ✅ Standalone executable (No installation required)
- ✅ Modern Steam-inspired UI
- ✅ Batch image conversion
- ✅ Full DDS support (BC1 / BC3 / BC5)
- ✅ GIF frame extraction
- ✅ Video → GIF / Image Sequence
- ✅ Estimated GIF size
- ✅ Drag & Drop support
- ✅ Multi-threaded processing
- ✅ Multi-language interface
- ✅ Automatic settings saving

---

# 📸 Features

## Image Conversion

Supports converting between:

- DDS
- TGA
- PNG
- JPG
- BMP
- ICO
- WEBP
- GIF

Features:

- Batch conversion
- Folder conversion
- Drag & Drop
- Multi-threaded processing
- No UI freezing

---

## DDS Support

Built-in DDS encoder using Pillow BCN.

Available formats:

- Auto
- BC1 (DXT1)
- BC3 (DXT5)
- BC5
- Uncompressed

No external DDS tools are required.

---

## GIF Frames

Extract every frame from GIF animations.

Export formats:

- PNG
- JPG
- TGA
- BMP
- WEBP
- DDS
- ICO

Supports:

- Export all frames
- Custom frame range
- Automatic numbering

---

## Video → GIF / Frames

Convert videos into:

- Animated GIF
- Individual image frames

Supported video formats:

- MP4
- AVI
- MOV
- MKV
- WEBM
- WMV
- FLV
- M4V
- 3GP
- MPG
- MPEG

GIF options include:

- FPS
- Width
- Loop count
- Palette size
- Dithering
- Transparency
- Optimization

---

## Estimated GIF Size

Before converting a video, PixelForge creates a short sample using your selected settings to estimate:

- Final dimensions
- Frame count
- Expected output size
- Low / High prediction range

This provides a much more accurate estimate than checking a single frame.

---

# 🌍 Supported Languages

PixelForge currently includes six languages:

- 🇺🇸 English
- 🇸🇦 العربية
- 🇫🇷 Français
- 🇷🇺 Русский
- 🇪🇸 Español
- 🇩🇪 Deutsch

The selected language is automatically saved and restored every time you launch the application.

---

# 🚀 Getting Started

Simply download **PixelForge Converter.exe**, extract the archive if needed, and run:

```
PixelForge Converter.exe
```

No installation is required.

---

# 💻 Requirements

- Windows 10 (64-bit)
- Windows 11 (64-bit)

The application is completely standalone.

**FFmpeg is only required if you want to use the Video tab.**

If FFmpeg is not found, only the Video features will be unavailable.

Everything else works normally.

---

# ⌨ Keyboard Shortcuts

| Shortcut | Action |
|-----------|--------|
| Ctrl + O | Select Folder |
| Ctrl + Shift + O | Select Files |
| Enter | Start Conversion |
| Esc | Clear Current List |
| Ctrl + 1 | Convert |
| Ctrl + 2 | GIF Frames |
| Ctrl + 3 | Video |

---

# 🛡 Virus Scan

PixelForge Converter is written entirely in **Python** and distributed as a standalone executable.

Because Python applications are commonly packaged using tools such as **PyInstaller**, some antivirus engines may incorrectly detect them as **False Positives**. This is unfortunately common with many Python applications and does **not** automatically mean the program is malicious.

You can verify the executable yourself using VirusTotal:

https://www.virustotal.com/gui/file/c3e9227cba0d11378f27bacaef495ff9f484fbbf9eb110f940ae1e5f74cae440?nocache=1

If you don't trust the application or you're not comfortable with the scan results, **please don't download or run it.**

Always verify software before executing it.

---

# ❤️ Credits

Developed by **CONTROL**

### Discord

```
control69
```

### More Projects

https://pay2win-store.vercel.app/

https://metin2.dev/profile/32316-control/

---

## License

Feel free to use this application for personal or commercial purposes.

If you redistribute it, please keep the original credits.

⭐ If you like the project, consider leaving a star.