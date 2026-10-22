# Harry's Knoll

A tiny painted world. Wander a grassy knoll, feed Harry the hedgehog, mow the lawn in stripes and dodge the wee lad, while days, rain, seasons and soft generative music drift by.

**Play:** https://hendoscott7.github.io/harrys-knoll/

## Controls

| Action | Keys |
| --- | --- |
| Walk | W A S D / arrows (Shift to hurry) |
| Turn | Drag |
| Zoom | Scroll |
| Feed Harry | F |
| Mow | M |
| Garden view | V |
| Sound on/off | N |
| Back to start | Esc |

On a phone: hold the lower left to walk, drag to turn, tap Harry to pet him.

## Things to know

- Your lawn saves in your browser, so your stripes are still there next visit.
- Harry naps in his house, comes out at night, and hides from the rain.
- Each real-world week brings a new season.
- Finish the lawn for a small celebration.

## Editing

The readable source is `src/index.html`. The live site serves a minified `index.html` built from it:

```
npm install
npm run build
```

Edit `src/index.html`, run the build, and commit both files. The giggle lives in `giggle.mp3` and loads after you step outside.

## Built with

One HTML file: [three.js](https://threejs.org/) r128, a hand-written painterly post-process, and Web Audio for the music. Giggle sound from the Freesound community.
