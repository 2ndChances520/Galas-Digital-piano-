🎹 GALA7V-1 // Polyphonic Analog Synthesizer
Model 2026 • Hardware Simulation via Web Audio API
External Image
External Image
External Image

GALA7V-1 is a fully functional, browser-based polyphonic analog synthesizer. It isn't just a "music player"—it is a sophisticated hardware simulation that recreates the tactile experience of a 2026-era boutique analog synth, complete with wood-grain chassis, CRT oscilloscopes, and sample-accurate sequencing.

**[🚀 Try the Live Demo]** <!-- Link your GitHub Pages here -->

🕹️ The Interface
The GALA7V-1 features a high-fidelity UI designed to mimic vintage studio gear:

Oscillator (VCO): Select between Sine, Square, and Sawtooth waveforms with integrated detune and glide controls.
Filter (VCF): A resonant 24dB/octave lowpass filter with an ADSR-modulated cutoff sweep.
Effects Suite:
BBD Delay: Classic Bucket Brigade Device simulation with feedback and mix.
Plate Reverb: Custom-generated Impulse Response (IR) for lush, metallic decay.
Drive: A WaveShaper-based saturation engine for harmonic grit.
Visual Feedback: Real-time CRT Oscilloscope and dual-channel VU Meters to monitor signal amplitude.
🎶 Built-in Sequencer
Switch between three pre-composed, high-energy tracks. Each track comes with its own optimized DSP preset:

Track	Style	BPM	Key Vibe
DISCO	Nu-Disco	124	Snappy basslines and rhythmic chord stabs.
BOSS BATTLE	Chiptune/Hardcore	172	Fast arpeggios, square waves, and relentless tension.
SYNTHWAVE	Retrowave	96	Atmospheric pads, deep delays, and cinematic sweeps.
🛠️ Technical Deep Dive
This project pushes the boundaries of what is possible within a single HTML file:

Sample-Accurate Scheduling: Uses a Web Worker to bypass the main thread's UI latency, ensuring the sequencer clock remains rock-solid even during heavy DOM manipulation.
Procedural Audio Generation: The Plate Reverb doesn't use an external sample; it uses a JavaScript algorithm to synthesize a custom Impulse Response buffer on startup.
Advanced CSS Rendering: Leverages complex radial-gradient layering, box-shadow depth, and repeating-linear-gradient to simulate physical materials like brushed metal, wood, and glowing CRT phosphor.
Dynamic DSP Engine: A polyphonic voice management system that handles note stealing, ADSR envelopes, and real-time parameter modulation via the Web Audio API.
🎹 How to Play
Click anywhere on the page to initialize the AudioContext (required by browser autoplay policies).
Use your Keyboard:
Lower Octave: Z, S, X, D, C, V, G, B, H, N, J, M
Upper Octave: Q, 2, W, 3, E, R, 5, T, 6, Y, 7, U, I
Use your Mouse: Click and drag the knobs, sliders, and switches to sculpt your sound in real-time.
📜 License
Distributed under the MIT License. See LICENSE for more information.

🤝 Credits
Developed as an exploration into the intersection of Web Audio DSP and High-Fidelity UI Design.
