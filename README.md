# bobosynth

A collection of original software instruments built with JUCE and released as both **Windows standalone applications** and **VST3 plug-ins**.

The current collection contains four instruments:

* **bobosynth TS-1** — analog-style polyphonic synthesizer
* **bobosynth EP-1** — modeled tine electric piano
* **bobosynth OR-1** — divide-down organ and string synthesizer
* **bobosynth OR-2** — nine-drawbar pulse-wave organ synthesizer

These instruments were designed as playable musical tools rather than strict recreations of particular vintage products. Their sound and interface draw on older electronic instruments, but each one has its own architecture, modulation system, effects, and factory preset library.

> This is an active personal instrument-design project. Interfaces, presets, parameter behavior, and file organization may continue to evolve.

---

## Instruments

### bobosynth TS-1

A voltage-controlled-style polyphonic synthesizer designed for broad analog textures, performance control, and industrial sound design.

Highlights:

* Polyphonic subtractive synthesis
* Oscillator, filter, envelope, and modulation controls
* Mod-wheel and aftertouch performance routing
* Integrated effects and output shaping
* A/B comparison
* Init and Panic controls
* Factory and user presets
* Large industrial preset selection
* MIDI-learn support
* Master output controls protected from preset recall

TS-1 is the general-purpose synthesizer in the collection: capable of basses, leads, pads, sequences, effects, metallic textures, and aggressive machine-like sounds.

---

### bobosynth EP-1

A physically inspired tine electric piano centered on velocity, resonance, pickup behavior, amplification, and speaker coloration.

Highlights:

* Modal resonator-based tine engine
* Velocity-sensitive hammer excitation
* Adjustable bite, bell, pickup position, and pickup distance
* Sustain, release, and expressive performance response
* Preamp drive and tone shaping
* Speaker and cabinet coloration
* Stereo tremolo, chorus, phaser, delay, and room reverb
* A/B comparison
* Init and Panic controls
* Factory and user presets
* Master and performance controls protected from preset recall

EP-1 is not presented as a clone of a specific historical electric piano. It is an original modeled instrument built around the musical behavior of struck tines, pickups, amplifiers, and speakers.

---

### bobosynth OR-1

A 1970s-inspired divide-down instrument combining organ ranks, string-machine behavior, paraphonic textures, and a substantial effects section.

Highlights:

* Twelve-generator divide-down oscillator architecture
* 16′, 8′, and 4′ ranks
* Saw and pulse-wave blending
* Polyphonic, paraphonic, mono, and legato modes
* Dedicated string section
* Three-line ensemble
* Phaser
* BBD-style flanger
* Dark stereo delay
* A/B comparison
* Init and Panic controls
* Factory and user presets
* Extensive industrial, drone, machine, signal, string, brass, and effects categories
* Master and performance controls protected from preset recall

OR-1 can behave like an organ, string ensemble, primitive polysynth, paraphonic synthesizer, or industrial sound generator depending on how its ranks, filters, envelopes, and effects are combined.

---

### bobosynth OR-2

A nine-drawbar organ synthesizer built from anti-aliased pulse oscillators rather than a conventional tonewheel model.

Highlights:

* Nine pulse-wave drawbar ranks
* Traditional organ footage relationships
* PolyBLEP anti-aliased oscillators
* Pulse-width control
* Rank-dependent pulse-width spread
* PWM rate and depth
* **Coherence** control, ranging from disciplined phase behavior to drifting ranks
* Normal, double, and triple unison modes
* Detune and stereo spread
* Key click
* Attack and release shaping
* Velocity response
* Sustain and pitch bend
* Mod-wheel PWM control
* Industrial drive
* 32-note polyphony
* Factory and user presets
* Init and Panic controls
* MIDI learn and a dedicated Oxygen Pro mapping

OR-2 is not a conventional Hammond-style emulation. It is closer to a polyphonic drawbar pulse synthesizer: organ logic used as the control surface for a more unusual oscillator instrument.

---

