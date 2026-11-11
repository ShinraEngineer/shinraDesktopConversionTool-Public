# Shinra Conversion Tool

A Windows file-conversion and AI-upscaling suite that lives in the right-click
menu. Hold **Shift** while you right-click a file or folder in File Explorer to
reach every action, each dispatched to the right backend and, for upscaling, to
your graphics card.

> **This is the public download and update feed.** The application source is
> private. Each release here carries the signed installer and the launcher
> update feed (`update.json`).

## Download

**[Download the latest release](https://github.com/ShinraEngineer/shinraDesktopConversionTool-Public/releases/latest)**

- Platform: **Windows x64**
- Installer: `ShinraConversionTool-<version>-win-x64-Setup.exe`
- Code-signed by **Shinra CC** (Authenticode, SHA-256, timestamped)

Run the installer (it needs administrator rights to register the machine-wide
context menus). After installing, hold **Shift** and right-click an image, a
document, a video, or a folder to see the **Shinra Conversion Tool** cascades.

## Features

- **Shift+Right-Click conversion** — every action is an Extended context-menu
  verb, so the cascades stay out of the normal right-click menu and appear only
  when Shift is held.
- **Real-ESRGAN GPU upscale** — Upscale x2 / x4 run the Real-ESRGAN ncnn-vulkan
  engine on your GPU, with a software-Vulkan (lavapipe) CPU fallback for
  machines without a usable GPU.
- **Image conversion** — convert among PNG, WebP, ICO, and alpha formats, and
  trace a raster image into a color or black-and-white SVG.
- **Document conversion** — PDF to text and image extraction; convert among
  Markdown, AsciiDoc, and plain text, and render them to PDF.
- **Video and audio conversion** — re-encode, remux, rescale, and change frame
  rate (FFmpeg), plus animated-image and audio targets.
- **ISO creation** — pack a folder into a UDF disc image.

## Updates

The in-suite [Shinra App Launcher](https://github.com/ShinraEngineer/launcherShinraApps)
checks this repository's release feed and offers one-click updates. The feed is
published as a release asset named `update.json` and always resolves at:

```
https://github.com/ShinraEngineer/shinraDesktopConversionTool-Public/releases/latest/download/update.json
```

## License and credits

The Shinra Conversion Tool is published by Shinra CC. The installer bundles
third-party components under their own licenses, including ImageMagick, Inkscape,
FFmpeg (GPL-3.0-or-later), pandoc, Typst, poppler, VTracer, Mesa lavapipe, and
the Real-ESRGAN ncnn-vulkan engine and model weights. Each component's license
text ships inside the installed application.
