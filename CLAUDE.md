# QR Generator Project

## Overview
This is a static web application that generates QR codes for documentation stickers. It's a single-page application built with vanilla HTML, CSS, and JavaScript.

## Project Structure
```
qr-gen/
├── docs/
│   └── index.html    # Main application file
└── README.md         # Basic project description
```

## Technology Stack
- **HTML5** - Structure and layout
- **CSS3** - Styling with modern gradient backgrounds and responsive design
- **Vanilla JavaScript** - Application logic
- **qrcode-generator** - External library loaded via CDN (https://cdnjs.cloudflare.com/ajax/libs/qrcode-generator/1.4.4/qrcode.min.js)

## Features
- Generate QR codes in multiple sizes (0.5", 0.75", 1.0", 1.5" squares)
- All QR codes generated at 300 DPI for optimal print quality
- **Character counter** with 100 character limit for compact QR codes
- Print mode with size selection
- Download individual QR codes as PNG files
- Direct print functionality
- URL validation
- Responsive design with gradient purple background

## How It Works
1. User enters a URL in the input field
2. Application validates the URL format
3. Generates QR codes in 4 different sizes simultaneously
4. User can select a specific size to download or print via the Print Mode modal
5. QR codes use error correction level L (lowest) for compact size

## QR Code Sizes
- **0.5" (150px)** - Tiny, great for small spaces
- **0.75" (225px)** - Small, good balance
- **1.0" (300px)** - Medium, recommended for most uses (default)
- **1.5" (450px)** - Large, easy to scan from distance

## Dependencies
No build dependencies required. The application uses:
- qrcode-generator from CDN (no npm/node_modules)

## Development
This is a static site that can be:
- Opened directly in a browser (open `docs/index.html`)
- Served via any static web server
- Deployed to GitHub Pages, Netlify, Vercel, etc.

## Deployment
The site is likely served from the `/docs` folder, which is a common GitHub Pages configuration.

## Contact Information
Created by Jon Price - jon@n3rd-media.com (n3rd-media.com)

## Notes for Claude Code
- This is a static site with no build process
- No package.json or dependencies to install
- No tests or linters configured
- The entire application is self-contained in a single HTML file
- All JavaScript is inline (no separate .js files)
- All CSS is inline (no separate .css files)
