# PDF Library

A modern, feature-rich PDF reader and library management system built with vanilla JavaScript.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-green.svg)

## Demo

🔗 **[Live Demo](https://YOUR-USERNAME.github.io/pdf-library/)**

## Features

### Library Management
- Add PDFs via URL
- Grid and list view layouts
- Search by title, category, or tags
- Filter by favorites, progress, or status
- Sort by date, title, or reading progress
- Reading statistics dashboard

### PDF Reader
- Smooth page navigation
- Zoom controls (fit width, custom zoom)
- Page rotation
- Multiple themes (Light, Dark, Sepia, Night)
- Full-screen focus mode

### Annotations
- Text highlighting (5 colors)
- Sticky notes
- Freehand drawing
- Bookmarks with Ctrl+D

### Data Management
- Auto-save reading progress
- Resume where you left off
- Export bookmarks and highlights
- All data stored locally (localStorage)

## Quick Start

### GitHub Pages Deployment

1. Fork this repository
2. Go to **Settings** → **Pages**
3. Select **main** branch, **root** folder
4. Click **Save**
5. Access at `https://YOUR-USERNAME.github.io/pdf-library/`

### Local Development

```bash
git clone https://github.com/YOUR-USERNAME/pdf-library.git
cd pdf-library
python -m http.server 8080
# Open http://localhost:8080
```

## Usage

1. Open the library (index.html)
2. Click **➕ Add PDF** to add a PDF URL
3. Click any PDF card to open the reader
4. Use keyboard shortcuts for navigation

### Keyboard Shortcuts

| Key | Action |
|-----|--------|
| `←` `→` | Previous/Next page |
| `Home` `End` | First/Last page |
| `Ctrl +` `-` | Zoom in/out |
| `Ctrl 0` | Reset zoom |
| `Ctrl D` | Add bookmark |
| `F` | Focus mode |
| `Esc` | Exit focus mode |

## Project Structure

```
pdf-library/
├── index.html          # Library (landing page)
├── reader.html         # PDF reader
├── lib/
│   ├── pdf.min.js      # PDF.js library
│   └── pdf.worker.min.js
├── sample.pdf          # Demo PDF
└── .nojekyll
```

## Technologies

- **PDF.js** - Mozilla's PDF rendering library
- **Vanilla JavaScript** - No frameworks
- **CSS3** - Glassmorphism design
- **localStorage** - Data persistence

## Browser Support

- ✅ Chrome / Edge
- ✅ Firefox
- ✅ Safari
- ✅ Mobile browsers

## License

MIT License - feel free to use for personal or commercial projects.

## Credits

- [PDF.js](https://mozilla.github.io/pdf.js/) by Mozilla
- Sample PDF: TracemonKey Research Paper
