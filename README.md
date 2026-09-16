# Beat Maker — digital Hichord

A free, one-page browser instrument: a Hichord-style chord pad (7 chord buttons, key/scale, chord modifiers, arpeggiator, synth engine with filter, delay and reverb) plus a 16-step drum machine with synthesized kits, swing, presets, and record-to-file.

Everything is in `index.html` — no build step, no dependencies. Open it locally or deploy to Netlify (drag the folder in, or connect this repo; `netlify.toml` is included).

## Controls

- Chord pad: keys `1`–`7` play scale degrees I–VII. Hold `Shift` for 7ths, `Alt` for sus, `Ctrl` for minor/major swap.
- Tap pads: `Q W E R A S D F` play the 8 pads (Drums / Percussion / Bass / Melody). Drum taps can be recorded straight into the grid while playing.
- Sound: pick a Hichord-style preset (Piano, Pad, Pluck, Organ, Bell, Strings, Lead, Lo-fi) and shape it with Tone / Space / Length.
- Strum ribbon: drag across it to strum the current chord.
- `Space` starts/stops the sequencer.
- Record button captures the master output to a `.webm` audio file.
