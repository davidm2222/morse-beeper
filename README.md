# Morse Code Beeper

A retro-futuristic web app that converts text to morse code audio beeps with a telegraph operator aesthetic.

## Features

- **Real-time Translation**: Converts your text to morse code as you type
- **Audio Playback**: Plays morse code as authentic beeps (dots and dashes)
- **Visual Feedback**: Signal indicator pulses with each transmission
- **Standard Timing**: Follows official morse code timing conventions
- **Retro Design**: Telegraph/radio operator aesthetic with glowing amber accents

## Usage

1. Open `morse-beeper.html` in your web browser
2. Type your message in the text area
3. Click "▶ Play Morse" to hear it transmitted
4. Click "■ Stop" to interrupt playback
5. Watch the morse code translation appear below

## Morse Code Timing

- **Dot**: 80ms beep
- **Dash**: 240ms beep (3× dot length)
- **Symbol gap**: 80ms (between dots/dashes in a letter)
- **Letter gap**: 240ms (between letters)
- **Word gap**: 560ms (between words)
- **Frequency**: 650 Hz sine wave

## Supported Characters

- Letters A-Z
- Numbers 0-9
- Common punctuation: . , ? ' ! / ( ) & : ; = + - _ " $ @

## Technical Details

- Pure HTML/CSS/JavaScript (no dependencies)
- Web Audio API for sound generation
- Responsive design works on mobile and desktop
- No server required - runs entirely in the browser

## Browser Compatibility

Requires a modern browser with Web Audio API support:
- Chrome/Edge 23+
- Firefox 25+
- Safari 6+
- Opera 15+

## License

Feel free to use, modify, and distribute as you see fit.
