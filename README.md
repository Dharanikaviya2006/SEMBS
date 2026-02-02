# Event Photo Branding Tool

A frontend-only web application for adding branded logos to event photos.

## Features

- 📸 Upload photos from your device
- 🏷️ Automatic logo overlay (draggable, always visible)
- ✏️ Custom caption with automatic hashtags
- ⬇️ Download branded images
- 📤 Share via Web Share API (with fallback)
- 📱 Fully responsive and touch-enabled

## Setup Instructions

1. Place your logo file in the same directory as `index.html`:
   - Recommended: `he5logo.png` (PNG format)
   - Alternative: `he5logo.svg` (SVG format)
2. Open `index.html` in a web browser
3. Or deploy to GitHub Pages

**Note:** The app will try to load `he5logo.png` first, then `he5logo.svg`. If neither is found, it will automatically create a placeholder logo with "HE5" text.

A sample SVG logo (`he5logo.svg`) is included in this project.

## How to Use

1. Click "Upload Photo" to select an image
2. The logo will automatically appear in the top-left corner
3. Drag the logo to reposition it anywhere on the image
4. Enter a custom caption in the text field
5. Click "Download Image" to save your branded photo
6. Click "Share" to share via social media (or download + copy caption)

## Deployment to GitHub Pages

1. Create a new GitHub repository
2. Upload `index.html` and `he5logo.png`
3. Go to Settings → Pages
4. Select your branch and root folder
5. Save and visit your deployed site

## Technical Details

- Pure HTML, CSS, and Vanilla JavaScript
- No dependencies or external libraries
- No backend or API calls required
- Works completely offline after initial load
- Canvas-based image manipulation
- Logo is always 15% of image width
- Automatic hashtags: #he5solutions #itconsulting #remodeling

## Browser Compatibility

- Modern browsers (Chrome, Firefox, Safari, Edge)
- Mobile browsers (iOS Safari, Chrome Mobile)
- Web Share API support varies by browser and platform
- Fallback provided for browsers without Web Share API

## Files

- `index.html` - Complete application (standalone)
- `he5logo.png` - Your company logo (place in same directory)

---

Made for HE5 Solutions
