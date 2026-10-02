# A Little Birthday World for Avi — V3

V3 is the more interactive, photo-led version of the birthday site.

## Included now
- Real couple photos from the latest upload
- Cinematic hero with animated photo cards + mouse parallax
- Interactive birthday gift reveal
- Slow Ken Burns-style "memory reel" photo animation
- Handwritten/scrapbook love letter
- Interactive reasons cards
- "Open when..." modal messages
- Catch-5-hearts mini game
- Custom cute heart cursor on desktop
- Floating hearts + click sparkles
- Moving/suspicious button interaction
- Press-and-hold final reveal
- Dedicated voice-note cassette UI
- Responsive/mobile-friendly layout
- `prefers-reduced-motion` support

## Add your real voice note
Put a file called:

    voice-note.mp3

next to `index.html`.

The voice-note player will then use it.

## Optional: turn the memory reel into a real video
If you later record a short birthday video, the "memory reel" section can be upgraded to use an MP4 instead of the current animated photo treatment.

## Local preview
From this folder:

    python3 -m http.server 8000

Then open:

    http://localhost:8000

## Git versioning
For each version:

    git add .
    git commit -m "Add birthday website V3"
    git push

Recommended future commits:
- V3 — photo-led interactive birthday page
- V3.1 — real voice note
- V4 — real birthday video / extra memories
