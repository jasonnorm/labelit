# LabelIt

Custom 2.5″ × 0.75″ slab labels for Zion SlabMag cases, made in the browser.

**Live app:** https://jasonnorm.github.io/labelit/

## Features

- Year & set, player, parallel/description, card # and serial #
- Text size, Normal/Bold weight, text color, ALL CAPS
- Border color (picker, hex, presets) and thickness
- QR code from any URL
- Logo upload (left, center or right; auto-trimmed; resizable) with image effects
- Background image (auto-cropped) with opacity and image effects
- Double-sided fold-over labels, with an optional QR-code-only back
- 600 DPI PNG download, Letter-sheet printing with cut lines, or label-printer output

## Run locally

It's a single static file with no build step. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 5173
```

When printing, choose **100% / Actual size** so labels come out at exactly 2.5″ × 0.75″.
