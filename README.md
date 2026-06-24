This is an **interactive musical scales and modes reference guide** in Spanish. It's a single-page HTML application that functions as both an educational tool and a sound generator.

## Key Features:

**🎵 Scale Detector**
- Input musical notes (using English like C, D, E or Spanish like Do, Re, Mi)
- Automatically identifies the scale/mode from its interval structure
- Displays matching scales with their characteristics

**🔊 Audio Playback**
- Click any scale name to hear it played ascending then descending
- Uses Web Audio API with synthesized sawtooth waves
- Includes envelope control and low-pass filtering

**📊 Comprehensive Database**
Contains 40+ scales organized into 7 categories:
1. Pentatonic scales (5 entries)
2. Exotic scales (6 entries)
3. Derivations from Major scale (7 modes)
4. Derivations from Melodic Minor (7 modes)
5. Derivations from Harmonic Minor (7 modes)
6. Other exotic scales (4 entries)
7. Octatonic scales - Bebop & Diminished (4 entries)

**Each scale includes:**
- Name
- Interval structure (T=tone, S=semitone)
- Formula notation (1, 2, 3, #4, etc.)
- Theoretical description (character/origin)

The interface is responsive, works on mobile/desktop, and supports both ascending/descending playback with proper octave handling.
