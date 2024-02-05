# BrainWave Generator

This project is a simple, interactive brainwave generator built with HTML, CSS, and JavaScript. It uses the Web Audio API to generate binaural beats and isochronic tones, allowing users to adjust frequencies and the pulse rate through a web interface. The application also features a real-time oscilloscope visualization of the audio waveform, enhancing the user's engagement and experience.

## Features

- **Adjustable Frequencies**: Users can control two separate frequencies for the left and right audio channels.
- **Pulse Rate Control**: Adjust the pulse rate to modulate the sound, creating isochronic tones.
- **Real-time Oscilloscope Visualization**: Visual feedback of the audio waveform.
- **Dynamic Frequency Variance**: Periodically introduces slight variations to the frequencies, simulating a more natural and engaging listening experience.
- **Green Terminal-like Interface**: Aesthetic inspired by classic computer terminals, featuring green text on a black background.

## How It Works

The brainwave generator utilizes the Web Audio API to create oscillators for sound generation, a gain node for volume control, and an LFO (Low Frequency Oscillator) to modulate the amplitude of the sound, creating the pulse effect. The application also includes an analyser node for real-time audio waveform visualization rendered on a `<canvas>` element.

## Usage

To use the brainwave generator:
1. Adjust the frequency sliders to set the desired frequencies for each audio channel.
2. Use the pulse rate slider to adjust the modulation rate of the sound.
3. Click the "Play" button to start sound generation. The button will toggle to "Stop" to allow you to stop the sound.
4. Observe the real-time oscilloscope visualization that corresponds to the generated audio.

## Customization

Feel free to fork this project and customize it according to your needs. You can adjust the range of frequencies, the appearance of the interface, or add additional features like preset brainwave states for meditation, focus, or relaxation.

## Technologies Used

- HTML
- CSS
- JavaScript
- Web Audio API

## Running Locally

To run the brainwave generator locally, simply clone this repository and open the `index.html` file in a modern web browser that supports the Web Audio API.

## Science-Based Frequency Combinations

Here are some frequency combinations based on known brainwave states. These are intended for use with binaural or monaural beat generators to encourage the brain to "tune in" to a specific state.

### 1. Deep Relaxation
- **Frequency 1:** 100 Hz
- **Frequency 2:** 104 Hz
- **Pulse:** 4 Hz (Theta range)
- **Explanation:** Aims for Theta range to encourage deep relaxation, meditation, and creativity.

### 2. Focus and Concentration
- **Frequency 1:** 200 Hz
- **Frequency 2:** 215 Hz
- **Pulse:** 15 Hz (Beta range)
- **Explanation:** Utilizes Beta range to enhance focus, alertness, and problem-solving.

### 3. Deep Sleep Induction
- **Frequency 1:** 150 Hz
- **Frequency 2:** 154 Hz
- **Pulse:** 4 Hz (Delta range)
- **Explanation:** Delta range is used to induce deep sleep or restfulness.

### 4. Meditation and Mindfulness
- **Frequency 1:** 200 Hz
- **Frequency 2:** 210 Hz
- **Pulse:** 10 Hz (Alpha range)
- **Explanation:** Alpha range to aid in relaxation, calmness, and meditative states.

### 5. Quick Mental Refresh
- **Frequency 1:** 500 Hz
- **Frequency 2:** 520 Hz
- **Pulse:** 20 Hz (Beta range)
- **Explanation:** Beta range for a quick mental refresh during sustained tasks.

### 6. Creativity Boost
- **Frequency 1:** 300 Hz
- **Frequency 2:** 308 Hz
- **Pulse:** 8 Hz (Alpha/Theta border)
- **Explanation:** Border of Alpha and Theta for a mix of relaxation and alert awareness conducive to creativity.

### Notes on Usage
- **Range Considerations:** Actual frequencies are higher than brainwave frequencies, but the difference (pulse) is in the intended range.
- **Volume and Duration:** Use a comfortable volume and start with shorter periods to gauge reaction.
- **Consult Professionals:** If seeking therapeutic effects or have health concerns, consult a healthcare professional before use.

Use these combinations as tools for relaxation, focus, or creativity, not as medical treatment. Individual results may vary.
