# bobosynth + bobofx

A growing collection of original software instruments, audio effects, and utility plug-ins built with JUCE.

The bobosynth instruments take ideas from analog subtractive synthesis, divide-down organs and string machines, electric pianos, drum machines, and vintage electronic keyboards, then push those architectures into less conventional territory.

The bobofx series follows the same philosophy for effects: familiar audio-processing ideas are expanded through modulation, parallel signal paths, feedback, stereo motion, and the recurring idea of “Mass” — multiple related processing structures acting together.

---

## Current builds

The repository currently contains Windows x64 VST3 builds.

### bobofx

- `bobofxDL-1.vst3`
- `bobofxEN-1.vst3`
- `bobofxFS-1.vst3`
- `bobofxLF-1.vst3`
- `bobofxLM-1.vst3`
- `bobofxOSC-1.vst3`
- `bobofxPH-1.vst3`
- `bobofxFR-1.vst3`
- `bobofxRM-1.vst3`
- `bobofxRV-1.vst3`
- `bobofxVU-1.vst3`

### bobosynth

- `bobosynthDM1.vst3`
- `bobosynthMM-1.vst3`
- `bobosynthOR1.vst3`
- `bobosynthOR-2.vst3`
- `bobosynthOR-3.vst3`
- `bobosynthTS-1.vst3`

---

# Installation

Copy the desired `.vst3` file into the standard Windows VST3 directory:

```text
C:\Program Files\Common Files\VST3
```

Restart your DAW or rescan its plug-in folders.

The current builds are intended for Windows x64.

---

# bobosynth instruments

## bobosynth TS-1

A broad analog-style polyphonic synthesizer for basses, leads, pads, sequences, metallic textures, effects, and aggressive electronic sounds.

Highlights include:

- polyphonic subtractive synthesis
- oscillator, filter, envelope, and modulation controls
- mod-wheel and aftertouch routing
- integrated effects and output shaping
- MIDI learn
- factory and user presets
- Init, Panic, and A/B comparison

---

## bobosynth MM-1 — Massively Monophonic

A three-oscillator monophonic synthesizer that takes a classic ladder-filter signal path and deliberately makes one note enormous.

Highlights include:

- three anti-aliased oscillators
- triangle, saw, square, and pulse waveforms
- up to eight oscillator lanes per oscillator
- as many as twenty-four oscillators sounding a single note
- independent Mass and Spread controls
- oscillator tuning and pulse-width controls
- nonlinear mixer
- drive and feedback
- four-pole ladder-style filter
- dual contour generators
- glide and note-priority modes
- LFO
- aftertouch
- mod wheel
- velocity control
- extensive preset library

MM-1 is intended to make one note occupy an unreasonable amount of space.

---

## bobosynth OR-1

A divide-down organ and string synthesizer inspired by 1970s electronic keyboards.

Highlights include:

- twelve-generator divide-down architecture
- 16′, 8′, and 4′ ranks
- saw and pulse-wave blending
- polyphonic, paraphonic, mono, and legato modes
- dedicated string section
- three-line ensemble
- phaser
- BBD-style flanger
- dark stereo delay
- string, brass, drone, signal, machine, and industrial presets

OR-1 can behave like an organ, string ensemble, primitive polysynth, paraphonic synthesizer, or industrial sound generator.

---

## bobosynth OR-2

A nine-drawbar pulse-wave organ synthesizer that uses organ architecture as the control surface for a stranger polyphonic instrument.

Highlights include:

- nine drawbar ranks
- traditional organ footage relationships
- anti-aliased pulse oscillators
- pulse width and PWM
- rank-dependent spread
- Coherence control
- single, double, and triple unison
- detune and stereo spread
- key click
- attack and release
- velocity and sustain
- pitch bend
- drive
- MIDI learn
- MIDI-controller drawbar mapping

---

## bobosynth OR-3 — Bobolina

A divide-down string ensemble with a three-path ensemble engine, vintage phaser, unison, and drive.

Registrations include:

- Contrabass
- Cello
- Viola
- Violin
- Trumpet
- Horn

Additional controls include Crescendo, Sustain, Bass Volume, Tune, Master, multi-stage phasing, three-path BBD-style ensemble, unison, and selectable drive character.

Bobolina draws from classic string-machine ideas while using original code, graphics, presets, and extensions.

---

## bobosynth DM-1

A synthesized drum machine designed around the idea that every drum sound should remain editable down to the voice architecture.

Highlights include:

- fully synthesized drum voices
- kick
- snare
- toms
- hi-hats
- cymbals
- metallic percussion
- per-voice tuning, decay, tone, and level
- filtering and drive
- bit crushing
- sample-rate reduction
- independent delay and feedback
- built-in sequencing
- electronic, industrial, and experimental kits
- Init, Panic, A/B comparison, and preset support

---

# bobofx effects

## bobofx LF-1 — Massive Ladder Filter

A large-format nonlinear filter processor.

Highlights include:

- 24 dB and 12 dB low-pass modes
- band-pass and high-pass modes
- strong resonance
- input drive
- bipolar envelope follower
- LFO modulation
- MIDI note tracking
- single, double, and triple Filter Mass
- feedback
- stereo movement
- Dry/Wet control

---

## bobofx PH-1 — Massive Phaser

A multi-stage phaser with deep modulation and parallel phase networks.

Highlights include:

- 4-, 6-, 8-, and 12-stage modes
- positive and negative feedback
- multiple LFO waveforms
- stereo phase offset
- envelope-follow modulation
- single, double, and triple Phase Mass
- network spread
- drift
- Dry/Wet control

It can operate as a conventional phaser, a wide stereo animation processor, or something considerably less polite.

---

## bobofx RM-1 — Massive Ring Modulator

A wide-ranging ring- and amplitude-modulation processor.

Highlights include:

- carrier frequencies from tremolo speeds to audio rate
- sine, triangle, square, and saw carriers
- continuous Tremolo-to-Ring control
- fine tuning
- MIDI-controlled carrier tracking
- pitch-bend response
- LFO and envelope modulation
- stereo counter-tuning
- single, double, and triple Carrier Mass
- drift
- drive
- feedback
- Dry/Wet control

RM-1 ranges from subtle tremolo through tuned harmonic processing to metallic sidebands and unstable machinery.

---

## bobofx DL-1 — Massive Analog Delay

A dark, modulated delay for slapback, dub, rhythmic echoes, ambient feedback, and unstable experiments.

Highlights include:

- approximately 5 ms to 2 seconds of delay time
- host synchronization
- manual tempo
- positive and negative feedback
- nonlinear saturation in the feedback path
- Ping Pong
- Freeze
- BBD Age
- tone filtering
- multiple modulation waveforms
- single, double, and triple Delay Mass
- stereo offset
- equal-power Dry/Wet control

The Mass architecture uses additional parallel delay structures without turning every tap into another mutually reinforcing feedback loop.

---

## bobofx FS-1 — Massive Frequency Shifter

A true single-sideband frequency shifter rather than a conventional pitch shifter.

Highlights include:

- shifts from extremely slow movement into the kilohertz range
- Up, Down, and Dual sideband modes
- through-zero modulation
- positive and negative feedback
- LFO and envelope modulation
- stereo counter-shifting
- MIDI note tracking
- single, double, and triple Shift Mass
- mass spread
- carrier drift
- latency-compensated Dry/Wet processing

FS-1 works particularly well for slow spectral rotation, metallic transformation, percussion, stereo movement, and feedback experiments.

---

## bobofx RV-1 — Polyspace Reverb

A creative reverb paired with a polyphonic spectral octave engine.

Highlights include:

- Chamber, Sky, and Void spaces
- modulated feedback-delay-network reverb
- diffusion
- damping
- stereo width
- Freeze
- tempo-synchronized predelay
- Sub −1
- Octave +1
- High +2
- multiple octave-routing modes
- Into Space and Orbit controls
- spectral processing
- conventional rooms and halls
- shimmer and cascading feedback textures

RV-1 can function as a conventional reverb, shimmer processor, octave effect inside a room, or a regenerative spectral instrument.

---

## bobofx LM-1 — Transient Maximizer

A two-stage loudness processor designed to retain or rebuild transient structure while enforcing a brickwall ceiling.

Highlights include:

- clean lookahead limiting
- program-dependent release
- Transients control
- detector-frequency focus
- pre-limiter peak shaving
- stereo-link control
- selectable lookahead modes
- oversampled true-peak safety stage
- dedicated ceiling control
- input/output and gain-reduction metering
- peak-hold indicators

LM-1 separates fast transient information from the slower body of a signal, allowing average level and waveform shape to be manipulated somewhat independently.

---

## bobofx EN-1 — Ensembler

A large stereo chorus and ensemble processor built around the idea of turning the bobofx Mass architecture toward unison.

Rather than treating chorus as one modulated delay line, EN-1 builds a moving population of related voices.

Highlights include:

- multi-voice ensemble processing
- unison / Mass-style voice structures
- stereo spread and motion
- orbit visualization
- variable modulation behavior
- multiple LFO waveforms
- sample-and-hold modulation
- organic and randomized motion
- assignable LFO destination
- MIDI learn and MIDI control
- smoothing of discontinuous modulation shapes to avoid unwanted clicks
- Dry/Wet control

EN-1 moves from subtle widening and vintage ensemble behavior into huge animated stereo chorusing.

---

## Additional utilities and processors

The current collection also includes:

### bobofx FR-1

`bobofxFR-1.vst3`

### bobofx OSC-1

`bobofxOSC-1.vst3`

### bobofx VU-1

`bobofxVU-1.vst3`

More detailed documentation for these units will be added as the collection is organized for release.

---

# Development status

These are active personal-development builds.

They are being released primarily so that the instruments can be played, tested, explored, and preserved as the collection develops.

Some processors intentionally permit:

- strong resonance
- high feedback
- self-oscillation
- extreme modulation
- substantial gain

Begin experimenting with monitoring levels reduced.

Some plug-ins may introduce latency when spectral processing, lookahead, oversampling, or similar DSP is active.


---

# Built with JUCE

All instruments and effects are built in C++ using the JUCE application and audio framework.

---

# License

No open-source license is currently specified.

Unless a separate license is added, the software, source code, presets, graphics, and included assets remain under their default copyright protection and are not automatically licensed for redistribution, modification, or reuse.

---

# About the project

bobosynth and bobofx are an ongoing collection of experimental musical software developed as a laboratory for synthesis, signal processing, interface design, and strange ideas about what an electronic instrument can be.
