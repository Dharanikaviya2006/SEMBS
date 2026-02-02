# Logo Setup Guide

## Using Your Own Logo

### Option 1: PNG Format (Recommended)
1. Save your logo as `he5logo.png`
2. Place it in the same directory as `index.html`
3. Recommended size: 400x400px or larger
4. Transparent background works best

### Option 2: SVG Format
1. Save your logo as `he5logo.svg`
2. Place it in the same directory as `index.html`
3. SVG files scale perfectly at any size

### Option 3: Use the Provided Sample
- A sample logo (`he5logo.svg`) is included
- You can use it as-is or customize it
- Edit the SVG file in any text editor to change colors, text, etc.

## Converting SVG to PNG

If you have an SVG and want to convert it to PNG:

### Online Tools
- [CloudConvert](https://cloudconvert.com/svg-to-png) - Free online converter
- [Convertio](https://convertio.co/svg-png/) - Another free option
- [SVG to PNG Converter](https://svgtopng.com/) - Simple and fast

### Using Design Software
- **Adobe Illustrator**: File → Export → Export As → PNG
- **Inkscape** (Free): File → Export PNG Image
- **Figma** (Free): Select object → Export → PNG

### Using Command Line (Advanced)
If you have ImageMagick installed:
```bash
convert he5logo.svg -resize 400x400 he5logo.png
```

## Logo Requirements

- **Transparent background** recommended for best results
- **Square aspect ratio** works best (e.g., 400x400px)
- **High resolution** ensures quality on large photos
- **File size** should be under 1MB for fast loading

## Customizing the Sample Logo

The included `he5logo.svg` can be edited in any text editor:

1. Open `he5logo.svg` in a text editor
2. Find the `<text>` elements to change the text
3. Find the `<linearGradient>` to change colors
4. Save and refresh your browser

Example color values:
- Blue: `#667eea`
- Purple: `#764ba2`
- Green: `#10b981`
- Red: `#ef4444`

---

**Questions?** The app will automatically use a fallback logo if no file is found, so you can test the app immediately!
