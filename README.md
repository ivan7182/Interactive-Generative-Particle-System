# Generative Visual Experiments

A collection of **interactive, audio-reactive, and typographic generative art sketches** built with **canvas-sketch**.

This repository contains several visual experiments exploring motion, sound, interaction, and typography using JavaScript and creative coding tools.

---

## ✨ Sketches

### 1. Interactive Grid

A generative grid animation where lines rotate and scale based on noise functions and optional audio input.

Features:

* Noise-based motion
* Audio reactive scaling
* Dynamic color shifting
* Tweakpane controls

File:

```
square-interactive.js
```

---

### 2. Audio Reactive Grid

A grid of animated strokes reacting to frequency data from an audio track.

Features:

* Audio spectrum analysis
* Noise-driven animation
* Dynamic line width
* Real-time parameter control

File:

```
audio-grid.js
```

Required asset:

```
audio/lofi.mp4
```

---

### 3. Psytrance Text Spiral

A hypnotic spiral made from repeating characters forming a rotating typographic tunnel.

Features:

* Spiral motion system
* Wave distortion
* Glow effects
* Zoom and rotation controls
* Psychedelic typography animation

File:

```
psytrance-text.js
```

---

## 🛠 Tools & Libraries

This project uses:

* **canvas-sketch**
* **canvas-sketch-util**
* **tweakpane**
* **Web Audio API**

---

## 📦 Installation

Install dependencies:

```
npm install
```

---

## ▶ Running a Sketch

Example:

```
canvas-sketch sketches/square-interactive.js --open
```

Or run other sketches:

```
canvas-sketch sketches/audio-grid.js --open
canvas-sketch sketches/psytrance-text.js --open
```

---

## 🎛 Controls

Many sketches include **Tweakpane UI controls** allowing you to adjust parameters such as:

* grid density
* animation speed
* color
* audio reactivity
* glow effects
* zoom and rotation

## 🎨 Concept

These sketches explore:

* generative motion
* sound visualization
* interactive graphics
* procedural animation
* typographic motion systems

The goal is to experiment with **creative coding techniques** and develop visual systems that react to interaction, time, and sound.

---

