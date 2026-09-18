# Hichord — Beat Maker

A free, one-page browser instrument: a Hichord-style chord pad (7 chord buttons, key/scale, chord modifiers, arpeggiator, synth engine with filter, delay and reverb) plus a 16-step drum machine with synthesized kits, swing, presets, and record-to-file.

Everything is in `index.html` — no build step, no dependencies. Open it locally or deploy to Netlify (drag the folder in, or connect this repo; `netlify.toml` is included).

## Controls

- Chord pad: keys `1`–`7` play scale degrees I–VII. Hold `Shift` for 7ths, `Alt` for sus, `Ctrl` for minor/major swap.
- Tap pads: `Q W E R A S D F Z X C V` play the 12 pads (Drums / Percussion / Bass / Melody). Drum taps can be recorded straight into the grid while playing.
- Sound: pick a Hichord-style preset (Piano, Pad, Pluck, Organ, Bell, Strings, Lead, Lo-fi) and shape it with Tone / Space / Length.
- Strum ribbon: drag across it to strum the current chord.
- `Space` starts/stops the sequencer.
- Loop pedals: `L` records/overdubs a 1–8 bar loop of anything you play (chords, strum, pads, melody); `Backspace` undoes the last layer.
- Record button captures the master output and downloads a 16-bit `.wav`.

## Use it on an iPad / phone with no Wi-Fi

1. Open the Netlify URL once in Safari (or Chrome on Android).
2. Tap **Share → Add to Home Screen**.
3. Launch it from the home screen icon. It is now installed and runs fully offline
   (service worker caches the whole app; there are no external dependencies).

Songs are saved inside the browser (Songs panel under **Studio**), auto-restore on relaunch,
and can be exported/imported as `.hichord.json` files to back up or move between devices.

## Hardware-style controls

- Gray **KEY**, yellow **SOUND**, red **KIT** buttons cycle key / sound (18) / drum kit (16). Shift-click goes backwards.
- ▲ / ▼ (or arrow keys ↑ ↓) change octave, even while a chord is held.
- Pads: Drums · Perc · Bass · Keys · Lead · FX. **Auto bass** plays your chord's root on every kick.
