# Harmonic Intervals Audio Dataset

## Description

This dataset contains 4,276 audio files in WAV format, each with a duration of 2 seconds. The dataset is designed for research on harmonic intervals in music. Harmonic intervals are pairs of notes played simultaneously, representing the distance between two pitches.

**DOI:** [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18065723.svg)](https://doi.org/10.5281/zenodo.18065723)

## Dataset Structure

The dataset is organized in the following hierarchical structure:

```
harmonic-intervals-audio-dataset/
├── original/          # Original audio recordings
├── up_semitone/      # Audio recordings with semitone increase
└── down_semitone/    # Audio recordings with semitone decrease
```

Each of these three folders contains 12 subfolders corresponding to musical intervals. Intervals are named by their size (2nd, 3rd, 4th, etc.) and quality (major, minor, perfect):

- **major_2nd** - Major second (2 semitones)
- **major_3rd** - Major third (4 semitones)
- **major_6th** - Major sixth (9 semitones)
- **major_7th** - Major seventh (11 semitones)
- **minor_2nd** - Minor second (1 semitone)
- **minor_3rd** - Minor third (3 semitones)
- **minor_6th** - Minor sixth (8 semitones)
- **minor_7th** - Minor seventh (10 semitones)
- **perfect_4th** - Perfect fourth (5 semitones)
- **perfect_5th** - Perfect fifth (7 semitones)
- **perfect_8th** - Perfect octave (12 semitones)
- **tritone** - Tritone (augmented fourth/diminished fifth, 6 semitones)

Each interval folder contains two subfolders with different dynamic levels:
- **forte** / **forte_up** / **forte_down** - Forte (louder, f)
- **piano** / **piano_up** / **piano_down** - Piano (softer, p)

Each folder contains approximately 56-60 audio recordings.

**Example file path:**
```
original/major_3rd/forte/major_3rd_000_forte.wav
```

## Statistics

- **Total files**: 4,276
- **Duration**: 2 seconds per file
- **Format**: WAV
- **Channels**: Mono
- **Bit depth**: 16-bit
