# Inner Voice

An audio visualization experiment that creates an interactive visual representation of sound using SVG animations. The visualization consists of five elements that respond to different frequency ranges of audio input.

## Live Demo

Visit [https://koryunhills.github.io/inner-voice/](https://koryunhills.github.io/inner-voice/) to try it out!

## Features

- Real-time audio visualization using Web Audio API
- SVG-based animations
- Frequency band analysis
- Microphone input support
- Device selection support
- Responsive design

## Local Setup

1. Clone the repository:
```bash
git clone https://github.com/koryunhills/inner-voice.git
cd inner-voice
```

2. Open `index.html` in a modern web browser.

3. Click "Start Microphone" and allow microphone access to begin visualization.

## How it Works

The visualizer splits audio input into five frequency bands:
- Bass (20-100 Hz)
- Low-mid (100-250 Hz)
- Mid (250-500 Hz)
- High-mid (500-2000 Hz)
- High (2000-8000 Hz)

Each SVG element responds to its corresponding frequency band, morphing between three states based on audio intensity:
- Default state (normal size)
- Contracted state (for low volumes)
- Expanded state (for high volumes)

## Browser Support

Requires a modern browser with Web Audio API support. 