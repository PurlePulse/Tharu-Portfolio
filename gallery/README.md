# Gallery Folder

Add your gallery images to this folder.

## How to Add Images

### Step 1: Add Image Files

Place your image files in this `gallery` folder.

### Step 2: Update the Image List in index.html

Open `index.html` and find the `galleryImages` array (around line 1031) and add your new image filename:

```javascript
const galleryImages = [
  "IMG-20251112-WA0018.jpg",
  "IMG-20251112-WA0020.jpg",
  // ... existing images ...
  "your-new-image.jpg", // Add your new image here
];
```

### Step 3: Refresh Browser

Refresh your browser to see the new images.

## Supported Formats

- JPG/JPEG
- PNG
- GIF
- WebP

## Features

- Responsive grid layout
- Click any image to view full-size in lightbox
- Close lightbox with X button, clicking outside, or Escape key
- Works without a web server (can open index.html directly)

## Note

The `gallery.json` file is kept as a reference but is not used by the website. When adding new images, update the `galleryImages` array in `index.html` directly.
