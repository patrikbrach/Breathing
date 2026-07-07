# Breathe

A minimalist guided breathing web app, designed for Safari on iPhone.

Press **Start**, follow a 3-2-1 countdown, then breathe with the circle: it expands as you breathe in, holds, and contracts as you breathe out.

## Technique

Uses the **4-7-8 relaxation method** (Dr. Andrew Weil):

- Breathe in through the nose for **4 counts**
- Hold for **7 counts**
- Breathe out slowly through the mouth for **8 counts**
- Repeat for **4 cycles**

Counts are paced as slow, relaxed beats (~1.4 s each) rather than literal seconds, so the rhythm never feels rushed — a full session is about two minutes.

## Features

- Black / white / light-gray minimalist design with the native iOS system font
- Animated breathing circle with a per-phase progress ring and beat countdown
- Gentle sound cues at each phase change (rising tone to breathe in, low tone to breathe out) so the exercise works with eyes closed — toggle top-right, remembered between visits; note that iPhone's silent switch mutes them
- Installable as a home-screen app: web manifest, matching black icon, and a service worker that makes it launch instantly and work fully offline
- iPhone Safari optimizations: safe-area insets, no tap highlight or double-tap zoom, dynamic viewport height
- Screen wake-lock keeps the display on during the exercise (where supported)
- Session pauses automatically if you switch away from the tab
- Respects `prefers-reduced-motion`

## Running it

The app is a single dependency-free file: open `index.html` in a browser, or host it anywhere static (GitHub Pages works out of the box).
