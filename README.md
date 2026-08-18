# Creature LIVE – TikTok Overlay V2

Real artwork extracted from your reference image + hatch & evolution animations.

## What's new in V2

- **Real transparent PNGs** of every stage from your dragon/wolf sheet
- **Ice / Shadow / Fire** dragons
- **Spirit / Shadow / Golden** wolves
- **Egg → Hatchling/Pup → Young → Adult → Ancient/Alpha → Legendary**
- Hatch animation (special when leaving the egg)
- Evolution spin + glow animation
- Crack animation on high gifts while still an egg
- Particle bursts on hatch / evolve / big gifts
- Everything from V1 still works (localStorage, Overlay Mode, TikFinity WebSocket, control panel)

## How to use

1. Open `index.html` in a browser (must keep the `assets/` folder next to it).
2. Select Dragon or Wolf + color line.
3. Click gift buttons or use the manual controls to watch it grow.
4. Toggle **Transparent Overlay Mode** when adding as Browser Source in OBS / TikTok LIVE Studio.

## Folder structure

```
creature-live/
├── index.html
├── README.md
└── assets/
    ├── egg_*.png
    ├── dragon_ice_*.png
    ├── dragon_shadow_*.png
    ├── dragon_fire_*.png
    ├── wolf_spirit_*.png
    ├── wolf_shadow_*.png
    └── wolf_golden_*.png
```

## TikFinity

Paste the WebSocket URL from the TikFinity Desktop App into the field and click Connect.
The event adapter is isolated so it can be adjusted later if the payload format changes.

## Hosting

Upload the whole folder (including `assets/`) to GitHub Pages or any static host.
