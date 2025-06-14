# Sound Counter

Sound Counter is a web application that counts significant sounds detected by your microphone, after a moment of silence. It is designed for use cases like mantra counting, meditation, or any activity where you want to increment a counter by making a sound (such as a clap, bell, or chant).

## Features

- **Real-time Sound Detection:** Counts a sound only after a period of silence, reducing false positives.
- **Customizable Thresholds:** Adjust the sensitivity for silence and sound detection, and set how long silence must last before a sound is counted.
- **Target Count Alert:** Plays a gentle alert sound when your chosen count is reached.
- **Microphone Test:** Visualize your mic input and test levels before starting.
- **Responsive UI:** Clean, mobile-friendly interface built with Tailwind CSS.

## Usage

1. **Open the app in your browser.**
2. **Click "Test Mic"** to check your microphone input and adjust your environment.
3. **Adjust Settings:**
    - **Silence Level:** Set the background noise level to consider as "silent".
    - **Sound Level:** Set how loud a sound must be to be counted.
    - **Silence Duration:** Set how long it must be silent before listening for a sound.
    - **Target Count:** Set the count at which an alert sound will play.
4. **Click "Start"** to begin listening. Make a sound (e.g., clap, bell, chant) after a moment of silence to increment the counter.
5. **Click "Reset"** to reset the counter at any time.

## How It Works

- The app uses the Web Audio API to access your microphone and analyze the audio stream.
- It waits for a period of silence, then listens for a sound above your chosen threshold.
- Each qualifying sound increments the counter.
- When the counter reaches your target, a gentle alert sound is played.

## Requirements

- A modern browser with microphone access (Chrome, Edge, Firefox, Safari).
- No installation required.

## Privacy

All audio processing happens locally in your browser. No audio is sent to any server.

## Credits

- UI built with [Tailwind CSS](https://tailwindcss.com/)
- Fonts from [Google Fonts](https://fonts.google.com/)

---

> **Note:** This project is for personal or educational use. Always be mindful of privacy and security when using microphone-enabled applications.
