# Vocal Processing and Mixing Project

## Overview

This project provides Python scripts for advanced vocal processing and mixing. The scripts enable users to manipulate vocal tracks by reducing silences, speeding up the audio, applying delay-based reverb effects, and mixing the processed vocals with a beat. The project is structured into two main steps:

1. **Working Step 1:** Focuses on preprocessing the vocal track by reducing silences and speeding up the audio.
2. **Working Step 2:** Applies a simple delay-based reverb effect and mixes the processed vocals with a beat track.

These scripts are designed to be part of a Jupyter Notebook workflow but can be easily adapted for standalone Python applications.

## Installation

To run these scripts, you will need Python 3.x and the following packages:
- `numpy`
- `librosa`
- `soundfile`
- `audioread`

You can install these packages using pip:

```bash
pip install numpy librosa soundfile audioread
```
## Usage

### Working Step 1: Preprocess Vocals

- Load an audio file.
- Reduce silences within the audio.
- Speed up the audio without changing the pitch.
- Save the processed audio to an output file.

```python
# Example usage
process_audio(vocals_file="path/to/vocals.wav", output_path="path/to/processed_vocals.wav")
```

### Working Step 2: Apply Reverb and Mix with Beat

- Load the processed vocals and a beat track.
- Optionally, apply pitch shifting to the vocals.
- Apply a simple delay-based reverb effect.
- Mix the vocals with the beat track, adjusting the start time and volume as needed.
- Save the final mix to an output file.

```python
# Example usage
modify_vocals(vocals_file="path/to/processed_vocals.wav", beat_file="path/to/beat.wav", output_file="path/to/final_mix.wav")
```

## Project Structure and Development Stages

The Git repository for this project is organized into several folders, each representing a different stage in the development process of the code. These stages are labeled from MKI to MKIV, with each folder containing the code and resources relevant to that particular stage of development. This structure allows users to explore how the project evolved over time and understand the progressive enhancements made at each stage.

- **MKI:** The initial version of the project, containing the most basic implementation of the vocal processing features.
- **MKII:** Introduces improvements and optimizations based on the feedback and results from MKI.
- **MKIII:** Further refines the code with advanced processing techniques and prepares the groundwork for the final stage.
- **MKIV:** The current and most advanced version of the project, incorporating all previous improvements and introducing the final set of features.

We encourage users to explore these folders to gain insights into the development process and the iterative improvements that have been made to achieve the current state of the project.

## License

This project is open for all to use, but please ensure to include the following copyright statement when using or adapting this code:

```
Copyright (C) [Year] [Your Name]
```

Replace `[Year]` with the current year and `[Your Name]` with your full name.

## Acknowledgments

- The scripts use the `librosa`, `numpy`, `soundfile`, and `audioread` libraries for audio processing.
```