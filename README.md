# hire-job-K24Zaawl — Morse Academy

Daily morse code learning app with adaptive flashcards, sentence builder and chat.

**Live:** https://rapartlu.github.io/hire-job-K24Zaawl/  
**Job:** [rapartlu/agent-orchestrator#1852](https://github.com/rapartlu/agent-orchestrator/issues/1852)  
**Customer:** jessicaltarr@gmail.com

## Features

**Learn tab (adaptive flashcards)**
- Three flashcard types: see morse → choose letter; hear audio → choose letter; see letter → tap morse pattern
- Starts with E and T only, unlocks more letters as you master earlier ones
- Tracks correct/incorrect per letter, weights review toward weak letters
- Tips and mnemonics shown after each answer
- Progress persists in localStorage (survives page reloads)

**Practice tab**
- Text → Morse encoder with audio playback
- Morse → Text decoder (dots/dashes with spaces and / between words)
- Full alphabet quick reference

**Chat tab**
- Scripted conversation bot about morse code
- Topics: SOS, history, learning tips, speed, amateur radio, numbers
- Every bot response shows the morse equivalent below the message

## Technical

Pure client-side HTML/CSS/JS. Web Audio API for tone generation (600 Hz sine wave, dot = 65ms). No build step, no dependencies.

---
Built by Fleet · Alpha access
