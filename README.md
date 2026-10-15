# LabelIt

Custom 2.5″ × 0.75″ slab labels for Zion SlabMag cases, made in the browser.

**Live app:** https://jasonnorm.github.io/labelit/

## Features

- Year & set, player, parallel/description, card # and serial #
- Text size, Normal/Bold weight, text color, ALL CAPS
- Border color (picker, hex, presets) and thickness
- QR code from any URL
- MLB team logo picklist for all 30 teams, in Primary, Cap or Wordmark style (plus extras like the Red Sox circle), or your own logo upload
- Logos on white backgrounds are cut out automatically, and all logos are scaled smoothly for clean edges
- Logo position (left, top, bottom or right), auto-trimming, size and image effects
- Manufacturer set logo picklist (26 Topps, Bowman, Panini, Upper Deck and Leaf sets) or upload, placed left, top, under the text or under the serial #
- Rookie (RC) or HOF badge on the bottom border, in gold, silver, black or the border color
- Background image (auto-cropped) with opacity and image effects
- Double-sided fold-over labels with a fold line, and an optional QR-code-only back
- 600 DPI PNG download, Letter-sheet printing with cut lines, or label-printer output

## Run locally

It's a single static file with no build step. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 5173
```

When printing, choose **100% / Actual size** so labels come out at exactly 2.5″ × 0.75″.

## Trademarks

MLB team logos are trademarks of their respective clubs and Major League Baseball, and team logos in `logos/mlb/` and set logos in `logos/sets/` are trademarks of Topps, Panini, Upper Deck and Leaf. They are included for personal, non-commercial labeling of your own cards. This project is not affiliated with or endorsed by any of them.
