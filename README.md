# LabelIt

Custom 2.5″ × 0.75″ slab labels for Zion SlabMag cases, made in the browser.

**Live app:** https://jasonnorm.github.io/labelit/

## Features

- Year & set, player, parallel/description, card # and serial #
- Text size, Normal/Bold weight, text color, ALL CAPS
- Border color (picker, hex, presets) and thickness
- QR code from any URL
- Sport selector (Baseball, Basketball, Football) that switches the team logos, team colors and ballparks/arenas offered
- NBA team logo picklist for all 30 teams (Primary, Full logo, and Vintage for 6 teams), plus 29 current and 11 historic arena backgrounds (Boston Garden, Chicago Stadium, Oakland Arena…)
- NFL team logo picklist for all 32 teams (official nfl.com logos, plus Vintage for 19 teams), with 32 current and 15 historic stadium backgrounds (Soldier Field 1927, Texas Stadium, the Polo Grounds…)
- MLB team logo picklist for all 30 teams, in Primary, Cap or Wordmark style, plus Vintage logos for 19 teams (e.g. Brooklyn Dodgers, Seattle Pilots, Montreal Expos) and extras like the Red Sox circle, or your own logo upload
- Logos on white backgrounds are cut out automatically, and all logos are scaled smoothly for clean edges
- Logo position (left, top, bottom or right), auto-trimming, size and image effects
- Manufacturer set logo picklist (28 Topps, Bowman, Panini, Upper Deck and Leaf sets) or upload, placed left, top, under the text or under the serial #
- Rookie (RC) or HOF badge on the bottom border, in gold, silver, black or the border color
- Background image: pick any of the 30 current MLB ballparks or 27 historic ones (Ebbets Field, Forbes Field, Tiger Stadium, the Astrodome…), or upload your own; full-width crop with an adjustable vertical position, opacity and image effects
- Double-sided fold-over labels with a fold line, and an optional QR-code-only back
- 600 DPI PNG download, Letter-sheet printing with cut lines, or label-printer output

## Run locally

It's a single static file with no build step. Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 5173
```

## Printing tips

- Choose **100% / Actual size** (not "Scale to fit") so labels come out at exactly 2.5″ × 0.75″.
- Use a regular paper size, **not a borderless one**. Borderless printing enlarges the image by a few percent, so labels print slightly too wide.
- To print a downloaded PNG, open it in **Preview**, not Photos; Preview uses the file's 600 DPI print size, Photos ignores it.

## Credits

Stadium and arena photos are from Wikimedia Commons under Creative Commons licenses; see [CREDITS.md](CREDITS.md) for each photographer and license.

## Trademarks

MLB team logos are trademarks of their respective clubs and Major League Baseball, and team logos in `logos/mlb/` and set logos in `logos/sets/` are trademarks of Topps, Panini, Upper Deck and Leaf. They are included for personal, non-commercial labeling of your own cards. This project is not affiliated with or endorsed by any of them.
