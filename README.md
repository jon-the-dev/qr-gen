# QR Code Generator

A simple, static web application for generating QR codes for documentation stickers.

**Live Site:** https://jon-the-dev.github.io/qr-gen/

## Features

- Generate QR codes in multiple sizes (0.5", 0.75", 1.0", 1.5" squares)
- All QR codes generated at 300 DPI for optimal print quality
- Download individual QR codes as PNG files
- Print mode with size selection
- URL validation
- Responsive design

## QR Code Sizes

| Size | Pixels | Use Case |
|------|--------|----------|
| 0.5" | 150px | Tiny - Great for small spaces |
| 0.75" | 225px | Small - Good balance of size and scannability |
| 1.0" | 300px | Medium - Recommended for most uses |
| 1.5" | 450px | Large - Easy to scan from distance |

## Usage

1. Enter a URL in the input field
2. Click "Generate QR Codes (All Sizes)"
3. Use "Print Mode - Select Size" to download or print a specific size

## Technology

- Vanilla HTML, CSS, and JavaScript
- [QRCode.js](https://github.com/davidshimjs/qrcodejs) for QR code generation
- No build process required

## Development

The entire application is contained in `docs/index.html`. Simply open the file in a browser or serve via any static web server.

## Deployment

Deployed via GitHub Pages from the `/docs` folder.

## License

AGPL-3.0

## Contact

Created by Jon Price - jon@n3rd-media.com
