# Beat Maker — digital Hichord

A free, one-page browser instrument: a Hichord-style chord pad (7 chord buttons, key/scale, chord modifiers, arpeggiator, synth engine with filter, delay and reverb) plus a 16-step drum machine with synthesized kits, swing, presets, and record-to-file.

Everything is in `index.html` — no build step, no dependencies. Open it locally or deploy to Netlify (drag the folder in, or connect this repo; `netlify.toml` is included).

## Controls

- Chord pad: keys `1`–`7` play scale degrees I–VII. Hold `Shift` for 7ths, `Alt` for sus, `Ctrl` for minor/major swap.
- Drums: `Q W E R T Y U I` trigger the 8 drum voices live. Click the grid to program steps.
- `Space` starts/stops the sequencer.
- Record button captures the master output to a `.webm` audio file.
