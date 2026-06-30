# PixelForge Converter v2.2

<p align="center">
  <img src="https://i.ibb.co/..." width="100%">
</p>

A modern image conversion tool built with **Python (PySide6)** featuring a clean Steam-inspired interface.

PixelForge Converter supports batch image conversion, GIF frame extraction, video-to-GIF conversion, and full DDS compression (BC1 / BC3 / BC5) without requiring any external DDS tools.

---

# Features

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
- Drag & Drop
- Folder conversion
- Multi-threaded processing
- No UI freezing

---

## Full DDS Support

Built-in DDS encoder using Pillow BCN.

Available formats:

- Auto
- BC1 (DXT1)
- BC3 (DXT5)
- BC5
- Uncompressed

No external DDS tools required.

---

## GIF Frame Extraction

Extract every frame from GIF files.

Export formats:

- PNG
- JPG
- TGA
- BMP
- WEBP
- DDS
- ICO

Supports:

- All frames
- Custom frame range
- Automatic numbering

---

## Video → GIF / Image Sequence

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

GIF settings include:

- FPS
- Width
- Loop count
- Palette size
- Dithering
- Optimize
- Transparency

---

## Estimated GIF Size

Before converting a video, PixelForge generates a short sample using your selected settings and estimates:

- Final dimensions
- Total frames
- Expected file size
- Low / High prediction range

This provides a much more realistic estimate than checking a single frame.

---

# Supported Languages

PixelForge currently includes six languages:

- 🇺🇸 English
- 🇸🇦 العربية
- 🇫🇷 Français
- 🇷🇺 Русский
- 🇪🇸 Español
- 🇩🇪 Deutsch

The selected language is automatically saved and restored on startup.

---

# Installation

```bash
pip install PySide6 Pillow
```

## Requirements

| Library | Purpose |
|----------|----------|
| PySide6 | User Interface |
| Pillow | Image Processing + DDS |
| FFmpeg | Required only for the Video tab |

If FFmpeg is missing, only the Video tab will be disabled.

Everything else works normally.

---

# Run

```bash
python image_converter_pro.py
```

---

# Keyboard Shortcuts

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

# Virus Scan

Since **PixelForge Converter is written entirely in Python**, some antivirus engines may incorrectly flag the executable as a **False Positive**, especially when packaged with tools such as PyInstaller.

You can verify the executable yourself using VirusTotal:

https://www.virustotal.com/gui/file/c3e9227cba0d11378f27bacaef495ff9f484fbbf9eb110f940ae1e5f74cae440?nocache=1

If you don't trust the application or the scan results, **please don't download or run it.**

Always verify software yourself before executing it.

---

# Credits

Developed by **CONTROL**

Discord

```
control69
```

More projects:

https://pay2win-store.vercel.app/

https://metin2.dev/profile/32316-control/

---

Please keep the original credits if you redistribute this project.