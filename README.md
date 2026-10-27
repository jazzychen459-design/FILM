# FILM — Tell the whole roll, not just three photos

FILM is an interactive prototype for a film-photography storytelling community. A phone camera lets you shoot a thousand photos and forget them; film gives you 36 frames, no delete, and a week of waiting — so every frame is a choice. FILM turns each roll into a story you can re-tell and share.

This is a **single-file, front-end prototype** built with vanilla HTML, CSS, and JavaScript. No build step, no framework, no back-end.

## Features

- **Whole-roll stories** — post a roll in the order you shot it, with one short "I thought" note under every frame.
- **Pull-the-film-out viewer** — friends scroll a 35mm film strip, frame by frame, exactly as it was shot.
- **Freeform Note** — re-tell a roll on a blank canvas: move, resize, and tilt photos, write on top, or try filters and thermal view. The original roll is never changed.
- **Community** — each roll is tagged with the film used (e.g. Kodak Gold 200), so strangers can discover real rolls and talk about them.
- **Tools** — find the right film with a short quiz, locate mail-in or partner labs with member pricing, and follow a shooting guide for different light.
- **Me** — edit your profile, check your stats, and scroll back through "My film journey" with a smooth half-circle dial.

## Run it

No installation needed. Just open the file in a browser:

```bash
# option 1: open directly
open index.html

# option 2: serve locally
python3 -m http.server 8000
# then visit http://localhost:8000
```

## Structure

```
index.html   # all markup, styles, and scripts in one self-contained file
```

All photos are loaded from remote URLs; no local assets are required.

## Tech stack

- Vanilla HTML / CSS / JavaScript (no framework, no build)
- SVG for the film-strip and timeline dial
- Web Audio for the dial's gear tick sound

## License

[MIT](LICENSE)
