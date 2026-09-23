# IMAGEOPS - Universal File & Document Processing Studio

> **Lightning-Fast, 100% Private In-Browser Document, PDF, Spreadsheet & Image Studio**

IMAGEOPS is an edge-native, zero-cloud bulk file conversion, compression, and document processing workstation engineered for developers, professionals, accountants, designers, and privacy-conscious teams.

All processing occurs **100% client-side** in your browser using modern Web APIs (`PDF.js`, `pdf-lib`, `SheetJS`, `JSZip`, `OffscreenCanvas`, and Web Workers). Your documents, spreadsheets, PDFs, and images never touch an external server. Zero uploads. Zero telemetry. Complete data confidentiality.

---

## Executive Design & Interface Architecture

- **Expansive 1540px Pro Workstation**: Optimized for wide modern monitors with multi-column dual-pane workbenches, giving side-by-side access to source file queues, live inspectors, and precision control decks.
- **Minimalist Executive Aesthetic**: Crafted with quiet discipline—obsidian & titanium monochrome surfaces, hairline 1px borders, subtle glassmorphic blur, and zero garish neon noise.
- **Hardware & Sandbox Telemetry Ribbon**: Real-time status indicators monitoring logical CPU concurrency, in-memory buffers, 0-byte outbound network isolation, and library pipeline versions.
- **Interactive Data Grid & Live Filter**: Real-time row filtering and columnar indexing across multi-sheet Excel and CSV datasets.
- **Zero Emojis**: 100% vector SVG iconography for an authentic, high-end developer and enterprise aesthetic.
- **Full Mobile Responsiveness**: Seamless adaptive layouts scaling smoothly down to 320px smartphones.

---

## Core Capabilities & Tool Modules

### 1. Bulk Image Studio
- **Modern Formats**: WebP, AVIF, JPEG, PNG, GIF, BMP, TIFF.
- **Dual-Pane Pro Workbench**: Side-by-side source reel metrics and sticky control deck with target codec selection, quality slider, and max resolution scaling (4K, 2K, 1080p, 1:1).
- **Visual Quality Inspector**: Interactive before-and-after split-screen comparison slider powered by GPU-accelerated CSS `clip-path`.
- **Batch Export**: Preserves folder directory structures and packages results into memory-buffered ZIP archives.

### 2. PDF to Word Converter
- **ECMA-376 OpenXML Generator**: Converts Adobe PDF documents into editable Microsoft Word (`.docx`) files entirely client-side.
- **Document Structure**: Preserves paragraphs, page breaks, headings, and text flow without transmitting confidential contracts or reports to external cloud APIs.

### 3. PDF to Excel & CSV Extractor
- **Tabular Data Recognition**: Scans PDF text streams, bounding coordinates, and tabular column layouts.
- **Dual Export Options**: Export structured PDF tables directly to Microsoft Excel (`.xlsx`) or comma-separated values (`.csv`).

### 4. PDF Size Compressor
- **Client-Side Optimization**: Compresses oversized scanned PDFs, presentations, and documents right in the browser.
- **Custom Density & Quality Presets**: Select from Web/Email (72 DPI), Balanced Office (150 DPI), or High-Res Print (200 DPI).
- **Real-Time Size Audit**: Displays before vs after byte counts and compression reduction percentages.

### 5. Excel & CSV Data Tools
- **Bidirectional Format Conversion**: Convert seamlessly between `.xlsx`, `.xls`, `.csv`, `.tsv`, and `.json`.
- **Live Spreadsheet Inspector**: In-browser paginated table viewer with real-time row search, row counting, and instant format exporting.

### 6. Images to PDF Merger
- **Document Assembly**: Combine collections of JPG, PNG, WebP, and AVIF photos into a single, polished PDF document.
- **Layout Control**: Configurable page formats (A4, US Letter, Fit to Image) and orientation (Auto, Portrait, Landscape).

---

## Security & Privacy Architecture

- **True Zero-Server Architecture**: Files are decoded, manipulated, and re-encoded in client memory. Disconnecting from the internet does not interrupt file processing.
- **Enterprise & Regulatory Compliance**: Naturally adheres to GDPR, HIPAA, and strict internal data residency policies because raw data never crosses the wire.
- **Zero Third-Party Telemetry**: Clean, privacy-first interface without tracking beacons or analytics cookies.

---

## Deployment & Getting Started

IMAGEOPS is distributed as a single, self-contained `index.html` file designed for instant static deployment.

### Deploy to Vercel
1. Fork or push this repository to GitHub.
2. Import the repository into your [Vercel Dashboard](https://vercel.com).
3. Framework Preset: **Other** (Root directory: `./`).
4. Click **Deploy**. Your suite is live globally in seconds.

### Local Usage
```bash
# Option A: Open directly in your browser
xdg-open index.html
# or
open index.html

# Option B: Run via local HTTP server
python3 -m http.server 8080
# Navigate to http://localhost:8080/
```

---

## Keyboard Shortcuts

| Key | Action |
| --- | --- |
| `T` | Toggle Dark / Light Theme |
| `M` | Toggle Synthesized Audio FX |
| `Esc` | Close inspector modals / Reset views |

---

## License

MIT License. Free for personal, commercial, and enterprise use.
