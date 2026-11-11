# Changelog

All notable changes to the Shinra Conversion Tool's public releases are recorded
here. Versions follow the Windows installer's version numbering.

## 3.4.0 - 2026-11-11

### Added

- **Over-the-network (OTN) updates.** The tool now checks this repository's
  release feed (`update.json`) for a newer version and surfaces the update, so
  the Shinra App Launcher can offer a one-click upgrade.

### Changed

- Unified the application and core version numbering on **3.4.0**.
- First public release of the Shinra Conversion Tool: a signed Windows installer
  plus the launcher update feed.

### Features in this release

- Shift+Right-Click conversion cascades registered machine-wide.
- Real-ESRGAN GPU upscale (Upscale x2 / x4) with a software-Vulkan CPU fallback.
- Image conversion (PNG / WebP / ICO / alpha) and raster-to-SVG tracing.
- Document conversion: PDF text and image extraction; Markdown / AsciiDoc / text
  conversion and rendering to PDF.
- Video and audio conversion (FFmpeg) and animated-image targets.
- Folder-to-UDF ISO creation.

The installer is code-signed by Shinra CC (Authenticode, SHA-256, timestamped).
