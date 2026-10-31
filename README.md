# Harmony

Browser lessons for learning music theory by playing. Every lesson has a keyboard you can play with a MIDI controller, your computer keys, or the on-screen piano.

## Pages

- `index.html` is the Chords page: six playable lessons on notes and intervals, scales, chords and inversions, harmony in a key (Roman numerals, tonic/subdominant/dominant, famous progressions), a gallery of chord types, and chord moves.
- `basslines.html` is the Basslines page: seven lessons on bass patterns and grooves, with a step sequencer.
- `synth.html` is the Synth page: seven lessons on sound synthesis (oscillators, filter, envelopes, LFO) with a playable synth, an oscilloscope, a spectrum view and an envelope graph. A switch turns knobs 1–8 into eight effects (drive, bit crush, ring mod, chorus, phaser, flanger, delay, reverb). Its knobs, faders and pads follow the Arturia MiniLab 3 factory layout, and any other controller can be mapped with Learn.
- `jazz.html` is the Jazz page: a one-year jazz piano practice plan based on Piano With Jonny's free lesson "The Jazz Piano 1-Year Practice Plan". Five pillars (scales, chords, voicings, lead sheets, improvisation) each have a beginner, intermediate and advanced exercise with a playable example, a metronome with swing, and a 12-month tracker (one key or one tune a month). The improvisation tools play a backing band and check your solo: target notes, neighbor approaches, or notes that fit each chord's scale.

## Controls

- **MIDI keyboard:** plug it in, then press the MIDI button in the header.
- **Computer keys:** `A` to `;` are white keys, `W E T Y U O P` are black keys, `Z` / `X` shift the octave.
- **On-screen piano:** click or tap keys. Multi-touch works for chords.

## Running it

Open `index.html` in **Chrome or Edge**. No build step or server needed.

### MIDI troubleshooting

- Safari and Firefox (without an add-on) don't support Web MIDI.
- Chrome asks for MIDI permission the first time. If you missed the prompt, allow MIDI devices in the site settings and reload.
- On Windows, close any DAW (e.g. Ableton) that is using the controller, or disable its input there.
- The MIDI pill in the header turns green and shows your device name once it's connected.
