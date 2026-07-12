# bobosynth + bobofx

A growing collection of original software instruments and experimental audio effects built with **JUCE**.

The repository contains ready-to-run **Windows standalone applications** and **VST3 plug-ins**. The instruments draw from classic subtractive, divide-down, electric-piano, organ, drum-machine, and string-ensemble architectures, while the effects explore large-format modular processing, spectral transformation, feedback, modulation, and mastering.

These are playable tools rather than strict museum-piece emulations. Vintage ideas are used as starting points, then extended into stranger territory.

---

## Downloads

For each product:

- use `.exe` for the Windows standalone version
- use `.vst3` inside a compatible DAW or plug-in host

The current builds are intended for **Windows x64**.

### VST3 installation

Copy the `.vst3` build to:

```text
C:\Program Files\Common Files\VST3
```

Then restart or rescan your DAW.

### Standalone use

Run the `.exe` directly.

Synthesizers and drum machines require MIDI input. Effects require both an audio input and audio output to be selected in the standalone audio settings.

---

# bobosynth instruments

## bobosynth TS-1

A broad analog-style polyphonic synthesizer built for basses, leads, pads, sequences, metallic textures, effects, and aggressive industrial sounds.

Highlights:

- polyphonic subtractive synthesis
- oscillator, filter, envelope, and modulation controls
- mod-wheel and aftertouch routing
- integrated effects and output shaping
- MIDI learn
- factory and user presets
- industrial preset library
- Init, Panic, and A/B comparison

---

## bobosynth EP-1

An original modeled tine electric piano focused on velocity, resonance, pickup behavior, amplification, and speaker coloration.

Highlights:

- modal resonator-based tine engine
- velocity-sensitive hammer excitation
- adjustable bite, bell, pickup position, and pickup distance
- preamp drive and tone shaping
- speaker and cabinet coloration
- tremolo, chorus, phaser, delay, and room reverb
- expressive performance response
- factory and user presets

EP-1 is not presented as a clone of one specific historical electric piano. It is an original instrument built around the musical behavior of struck tines, pickups, amplifiers, and speakers.

---

## bobosynth MM-1 — Massively Monophonic

A three-oscillator monophonic synthesizer with a classic ladder-filter signal path expanded into a much larger single-note instrument.

Highlights:

- three anti-aliased oscillators
- triangle, saw, square, and pulse waveforms
- up to eight oscillator lanes per oscillator
- as many as twenty-four oscillators on one note
- independent Mass, Spread, tuning, and pulse-width controls
- nonlinear mixer, drive, and feedback
- four-pole ladder-style filter
- dual contour generators
- glide and note-priority modes
- LFO, aftertouch, mod-wheel, and velocity control
- large factory preset library

MM-1 is intended to make one note occupy an unreasonable amount of space.

---

## bobosynth OR-1

A divide-down organ and string synthesizer inspired by 1970s electronic keyboards.

Highlights:

- twelve-generator divide-down architecture
- 16′, 8′, and 4′ ranks
- saw and pulse-wave blending
- polyphonic, paraphonic, mono, and legato modes
- dedicated string section
- three-line ensemble
- phaser, BBD-style flanger, and dark stereo delay
- extensive string, brass, drone, signal, machine, and industrial presets

OR-1 can behave like an organ, string ensemble, primitive polysynth, paraphonic synthesizer, or industrial sound generator.

---

## bobosynth OR-2

A nine-drawbar pulse-wave organ synthesizer rather than a conventional tonewheel model.

Highlights:

- nine drawbar ranks
- traditional organ footage relationships
- anti-aliased pulse oscillators
- pulse width and PWM
- rank-dependent spread
- Coherence control
- single, double, and triple unison
- detune and stereo spread
- key click, attack, release, velocity, sustain, and pitch bend
- industrial drive
- MIDI learn
- dedicated Oxygen Pro drawbar mapping

OR-2 uses organ logic as the control surface for a stranger polyphonic pulse synthesizer.

---

## bobosynth OR-3 — Bobolina

A divide-down string ensemble with six registrations, a three-path ensemble, vintage phaser, unison, and drive.

Highlights:

- Contrabass
- Cello
- Viola
- Violin
- Trumpet
- Horn
- Crescendo and Sustain controls
- Bass Volume, Tune, and Master
- three-path BBD-style ensemble
- vintage multi-stage phaser
- single, double, and triple unison
- Clean, Console, and Hot drive modes
- fifty factory presets

Bobolina is inspired by classic string machines and modern compact string modules, but uses original code, graphics, presets, and extensions.

---

## bobodrum DM-1

A synthesized drum machine designed for aggressive electronic rhythm programming and per-voice sound destruction.

Highlights:

- fully synthesized drum voices
- kick, snare, toms, hats, cymbals, and metallic percussion
- per-voice tuning, decay, tone, and level
- independent filtering and drive
- per-voice bit crushing and sample-rate reduction
- independent delay and feedback
- China-splash-inspired metal voice
- built-in sequencing
- industrial and experimental kits
- Init, Panic, A/B comparison, and preset support

DM-1 was built around the idea that every drum sound should remain editable all the way down to the voice architecture.

---

# bobofx effects

## bobofx LF-1 — Massive Ladder Filter

A large-format nonlinear filter effect.

Highlights:

- 24 dB and 12 dB low-pass modes
- band-pass and high-pass modes
- resonance into strongly resonant territory
- input drive
- bipolar envelope follower
- LFO modulation
- MIDI note tracking
- single, double, and triple Filter Mass
- feedback, stereo movement, and Dry/Wet control
- utility, motion, drum, guitar, bass, industrial, and FX presets

---

## bobofx PH-1 — Massive Phaser

A multi-stage phaser with deep modulation and parallel phase networks.

Highlights:

- 4-, 6-, 8-, and 12-stage modes
- positive and negative feedback
- sine, triangle, square, and random modulation
- stereo phase offset
- envelope-follow modulation
- single, double, and triple Phase Mass
- network spread and drift
- vintage, stereo, drum, guitar, keys, industrial, and FX presets

---

## bobofx RM-1 — Massive Ring Modulator

A wide-ranging ring-modulation and amplitude-modulation processor.

Highlights:

- carrier range from tremolo speeds to audio rate
- sine, triangle, square, and saw carriers
- continuous Tremolo-to-Ring control
- fine tuning
- MIDI-controlled carrier tracking
- pitch-bend response
- LFO and envelope modulation
- stereo counter-tuning
- single, double, and triple Carrier Mass
- drift, drive, feedback, and Dry/Wet control

RM-1 can move from gentle tremolo to metallic sidebands, unstable machinery, and tuned harmonic processing.

---

## bobofx DL-1 — Massive Analog Delay

A dark, modulated delay built for slapback, dub, rhythmic echoes, ambient feedback, and unstable experiments.

Highlights:

- 5 ms to 2 second delay time
- host synchronization and manual tempo
- positive and negative feedback
- nonlinear saturation inside the feedback loop
- Ping Pong
- Freeze
- BBD Age
- tone filtering
- sine, triangle, square, and random modulation
- single, double, and triple Delay Mass
- safe parallel feed-forward mass taps
- stereo offset and equal-power Dry/Wet control

The additional mass taps do not create multiple mutually reinforcing feedback loops, allowing very large echoes without uncontrolled gain multiplication.

---

## bobofx RF-1 — Massive Resonant Filter Bank

A moving bank of resonators that can function as an EQ, formant filter, sequenced spectral processor, or rotating mechanical vowel machine.

Highlights:

- 8-band and 12-band modes
- center frequency and semitone spacing
- resonance, morph, and spectral tilt
- envelope-follow modulation
- sine, triangle, stepped, and random motion
- stereo spectral rotation
- MIDI note tracking
- single, double, and triple Bank Mass
- smooth interpolation for continuous motion modes
- hard stepping retained for Stepped and Random modes

RF-1 often reveals harmonics one at a time, especially when fed a sawtooth wave. That articulated movement is part of its character.

---

## bobofx FS-1 — Massive Frequency Shifter

A true single-sideband frequency shifter rather than a pitch shifter.

Highlights:

- shift range from 0.05 Hz to 5 kHz
- Up, Down, and Dual sideband modes
- through-zero modulation
- positive and negative feedback
- LFO and envelope control
- stereo counter-shifting
- MIDI note tracking
- single, double, and triple Shift Mass
- mass spread and carrier drift
- latency-compensated Dry/Wet path

FS-1 is suited to slow barber-pole motion, metallic transformation, stereo motion, percussion processing, and extreme feedback experiments.

---

## bobofx RV-1 — Polyspace Reverb

A creative reverb paired with a polyphonic octave engine.

Highlights:

- Chamber, Sky, and Void spaces
- modulated feedback-delay-network reverb
- diffusion, damping, width, and freeze
- predelay with feedback and tempo sync
- polyphonic Sub −1, Octave +1, and High +2 voices
- selectable octave character
- Octave Tone and Octave Presence
- Front, Space, Hybrid, and Cascade octave-routing modes
- Into Space and Orbit controls
- latency-compensated spectral octave processing
- useful rooms, halls, shimmer spaces, industrial reverbs, and extreme regenerative presets

RV-1 can behave as a conventional reverb, a shimmer processor, a polyphonic octave pedal inside a room, or a cascading spectral feedback instrument.

---

## bobofx LM-1 — Transient Maximizer

A two-stage loudness processor designed to preserve or rebuild transient shape while enforcing a brickwall ceiling.

Highlights:

- clean lookahead limiter
- program-dependent release
- Transients control from dense to punchy
- detector-frequency focus
- pre-limiter peak shaving
- stereo-link control
- selectable lookahead modes
- oversampled true-peak safety stage
- dedicated brickwall ceiling fader
- vertical level and gain-reduction meters
- dB gradations
- peak-hold markers
- utility, mastering, drums, bass, synth, vocal, industrial, and extreme presets

LM-1 separates fast transient information from the slower body of the signal, allowing average level and waveform shape to be controlled more independently than with a conventional one-stage limiter.


---

# Notes

- These builds are under active development.
- Plug-ins may introduce latency when spectral processing, lookahead, or oversampling is active.
- Some presets intentionally approach unstable feedback, self-oscillation, or extreme loudness. Begin with monitoring levels reduced.

