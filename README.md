# Musical Bouncing Shapes

A creative web-based music generator that creates melodies through bouncing shapes and physics interactions. The project combines visual elements with sound synthesis to create an interactive audio-visual experience.

## Overview

This project features bouncing geometric shapes that generate musical notes when they collide with the ground. The position of each collision determines the pitch of the note, creating emergent melodies through physics-based interactions.

![Musical Bouncing Shapes Demo](reference.png)
*Reference image showing the interactive music generator interface*

## Features

### Audio
- Multiple synthesizer types including:
  - Basic waveforms (sine, square, triangle, sawtooth)
  - Bass sounds (TB-303, acid, sub bass, wobble)
  - Lead instruments (super saw, pluck, FM synth, PWM)
  - Classic instruments (piano, organ, bells, pad)
- Real-time audio parameter controls:
  - Volume and reverb
  - Filter cutoff and resonance
  - Attack and decay
  - LFO rate and depth
  - Octave shifting and detune
- Recording capabilities:
  - MIDI recording for musical notation and DAW import
  - High-quality WAV audio recording
  - Simultaneous MIDI and audio recording
  - Built-in audio playback preview
  - One-click download for both formats
  - File management system with audio preview
  - Automatic file naming with timestamps

### Visual
- Three types of bouncing shapes (circle, square, triangle)
- Dynamic shape creation and destruction
- Customizable visual effects:
  - Trail effects
  - Glow intensity
  - Color modes (random, gradient, monochrome, rainbow)
  - Particle interactions
  - Explosion effects
- Adjustable physics parameters:
  - Bounce intensity
  - Rotation speed
  - Particle size and count
- Minimum and maximum shape limits

### Interface
- Responsive design with collapsible controls
- Fullscreen mode
- Visual configuration panel
- MIDI file management system
- Randomization feature for all parameters

## How It Works

1. Shapes bounce around the screen following basic physics rules
2. When a shape hits the bottom of the screen:
   - It generates a musical note based on its X position
   - The note is played through the selected synthesizer
   - Visual effects (sparkles, trails) are created
   - The shape has a 15% chance to disappear (if above minimum shape count)
3. The piano keyboard at the bottom shows which notes are being played
4. Record your creation:
   - Click the record button to start recording
   - Both MIDI and audio are recorded simultaneously
   - Stop recording to save both files
   - Access your recordings through the Files panel

## Future Development

Currently, the project focuses on single-note melodies with one type of synthesizer playing at a time. Future enhancements could include:
- Polyphonic synthesis
- Multiple simultaneous instruments
- Rhythm patterns
- Harmony generation
- More complex physics interactions
- Additional visual effects and shape types
- MIDI import capability
- Preset system for saving configurations

## Technologies Used

- HTML5 Canvas for graphics
- Web Audio API for sound synthesis
- JavaScript for physics and interaction
- CSS for styling and animations

## Usage

Simply open the HTML file in a modern web browser. No additional dependencies or installation required. Click the refresh button to start a new session, adjust parameters using the control panel, and use the record button to save your favorite sequences as MIDI files.

### Recording Your Music

1. Click the "Record" button (⏺) to start recording
2. Create music by letting shapes bounce and interact
3. Click "Stop" (⏹) to end recording
4. Both MIDI and audio files will be saved automatically
5. Access your recordings through the Files panel (📁):
   - 🎹 MIDI files: Perfect for importing into DAWs or music software
   - 🔊 WAV files: High-quality audio recordings of exactly what you hear
   - Preview audio recordings directly in the browser
   - Download files by clicking on their names

### Browser Compatibility

For the best experience, use a modern browser that supports the Web Audio API and MediaRecorder:
- Chrome (recommended)
- Firefox
- Edge
- Safari (limited audio recording support)

Note: Audio recording requires browser support for MediaRecorder API. If audio recording is not supported in your browser, MIDI recording will still work. 