# Breathe

A minimalist guided breathing web app, designed for Safari on iPhone.

Press **Start**, follow a 3-2-1 countdown, then breathe with the circle: it expands as you breathe in, holds, and contracts as you breathe out.

## Technique

Uses the **4-7-8 relaxation method** (Dr. Andrew Weil):

- Breathe in through the nose for **4 seconds**
- Hold for **7 seconds**
- Breathe out slowly through the mouth for **8 seconds**
- Repeat for **4 cycles** (about 75 seconds)

## Features

- Black / white / light-gray minimalist design with the native iOS system font
- Animated breathing circle with a per-phase progress ring and second countdown
- iPhone Safari optimizations: safe-area insets, no tap highlight or double-tap zoom, dynamic viewport height
- Screen wake-lock keeps the display on during the exercise (where supported)
- Session pauses automatically if you switch away from the tab
- Respects `prefers-reduced-motion`

## Running it

The app is a single dependency-free file: open `index.html` in a browser, or host it anywhere static (GitHub Pages works out of the box).
