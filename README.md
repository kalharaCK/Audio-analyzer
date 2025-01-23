# Real-Time Enhanced Audio Analysis 🎵

## Overview
This project is a MATLAB-based real-time audio analysis tool that provides live visualization of audio signals in the time domain, frequency domain, and spectrogram. It also includes advanced audio filtering and recording capabilities, making it a great starting point for audio enthusiasts and researchers. 🎧

## Features
- **Real-Time Audio Analysis**: Capture and analyze audio signals live. 🟢
- **Time-Domain Visualization**: Displays the amplitude of the signal over time. ⏱️
- **Frequency-Domain Visualization**: Shows the magnitude spectrum using FFT. 📊
- **Spectrogram Display**: Dynamic spectrogram with customizable parameters. 🌈
- **Advanced Bandpass Filtering**: Filter audio signals between 300 Hz and 3000 Hz. 🎚️
- **Audio Recording**: Save audio frames as a `.wav` file with timestamped filenames. 💾
- **User Interaction**:
  - Visual indicators for recording. 🔴
  - Stop button to end the analysis gracefully. ✋
  - Error handling and user feedback for a smoother experience. ⚠️

## Installation
### Requirements
1. MATLAB (tested on R2022a or newer). 🖥️
2. Signal Processing Toolbox. 🛠️

### Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/enhanced-audio-analysis.git
   ```
2. Navigate to the project folder:
   ```bash
   cd enhanced-audio-analysis
   ```
3. Ensure the `recordings` directory exists or is created automatically by the script. 📂

## Usage
1. Open MATLAB and navigate to the project directory. 📍
2. Run the script:
   ```matlab
   EnhancedLiveAudioAnalysis
   ```
3. The live analyzer window will appear with three plots:
   - **Time-Domain Signal**: Shows the real-time waveform. ⏱️
   - **Frequency-Domain Signal**: Displays the magnitude spectrum. 📊
   - **Spectrogram**: Updates dynamically with live audio data. 🌈
4. Click the "Stop Recording" button to end the analysis and save the recording. ✋💾

## Script Highlights
### Audio Configuration
- **Sample Rate**: Configured at `3 * 44100` for high-resolution analysis. 🎶
- **Samples Per Frame**: Set to `1024` for efficient processing. ⚡

### Advanced Filtering
- Implements a 6th-order IIR bandpass filter to isolate frequencies between 300 Hz and 3000 Hz. 🎚️

### Spectrogram Parameters
- Uses a Hanning window, 50% overlap, and FFT size of 256 for clear visualization. 🌈

### Robust Error Handling
- Catches audio device errors and provides meaningful error messages. ⚠️
- Ensures proper cleanup of resources (e.g., releasing audio devices). 🧹

### Recording
- Automatically saves audio files in the `recordings` folder with a timestamped filename. 💾



### Enjoy experimenting with live audio analysis! 🎶

