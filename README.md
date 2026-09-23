# IMAGEOPS

> **Lightning-Fast, 100% Private Bulk Image Conversion & Compression Studio**

ImageOps is an edge-native, zero-cloud bulk image converter and compression suite engineered for photographers, web developers, designers, and privacy-conscious teams.

All processing occurs **100% client-side** in your browser using multithreaded Web Workers, `createImageBitmap`, `OffscreenCanvas`, and in-memory `JSZip` bundling. Zero server uploads. Zero telemetry.

---

## Features

- **100% Client-Side Privacy**: Images never leave your computer. Fully GDPR, HIPAA, and offline compliant.
- **Multithreaded Hardware Acceleration**: High-speed asynchronous decoding and rendering via Web Workers.
- **Directory Structure Preservation**: Drop entire folders; ImageOps preserves all nested directories in the downloaded ZIP.
- **Modern Formats Supported**:
  - **WebP**: 30% to 80% smaller than JPEG with alpha transparency.
  - **AVIF**: Next-gen extreme compression efficiency.
  - **PNG**: Pixel-perfect lossless clarity.
  - **JPEG**: Universal compatibility.
  - **GIF, BMP, TIFF**: Batch import and format modernization.
- **Interactive Quality Inspector**: Visual split-screen slider with GPU-accelerated CSS `clip-path` to compare original vs optimized images.
- **Synthesized Web Audio FX**: Tactile sound feedback and victory fanfares generated via the Web Audio API.
- **Dynamic Cosmic Themes**: Dark and Light themes with dynamic floating aurora mesh gradients.
- **Fully Mobile Responsive**: Streamlined layouts tailored for mobile, tablet, and desktop screens.

---

## Getting Started

Simply open `imageops.html` in any modern web browser:

```bash
# Option A: Open directly in your browser
xdg-open imageops.html
# or
open imageops.html

# Option B: Run via a simple local HTTP server
python3 -m http.server 8080
# Open http://localhost:8080/imageops.html
```

---

## Keyboard Shortcuts

| Key | Action |
| --- | --- |
| `T` | Toggle Dark / Light Theme |
| `M` | Toggle Synthesized Audio FX |
| `Esc` | Close comparison modal / Reset |

---

## License

MIT License. Free for personal and commercial use.
