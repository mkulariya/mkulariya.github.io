# mkulariya.github.io

Personal site for Manish Kulariya. One HTML file, no build step, no dependencies beyond three
webfonts.

**Live:** https://mkulariya.github.io

## Design

*Single Channel.* Pure greyscale, black through white, no hue anywhere. The hero name is
rasterised into a low resolution grid and resolved out of sensor noise in real time on a canvas:
each cell mixes its target value with decaying noise, then gets pushed through a five step grey
ramp with an ordered Bayer dither offset. Pointer movement re-noises the image locally.

Each career row carries a small hand drawn SVG of the signal that era actually read: an ECG trace,
a fundus and a lesion contour, a handwriting scrawl with an entity box, pose skeletons, bounding
boxes, a news firehose collapsing into one line. The glyphs stroke themselves in on scroll.

- Display: Martian Mono
- Body: Newsreader
- Utility: IBM Plex Mono

Respects `prefers-reduced-motion`, keyboard focus is visible, and it holds up down to 390px wide.

## Local

Open `index.html`. That is the whole workflow.
