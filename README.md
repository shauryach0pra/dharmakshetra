<div align="center">

### Dharmakshetra

</div>

<div align="center">

[![HTML](https://img.shields.io/badge/HTML-%23E34F26.svg?logo=html5&logoColor=white)](#) [![CSS](https://img.shields.io/badge/CSS-639?logo=css&logoColor=fff)](#) [![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=000)](#)

</div>

---

### Overview

Dharmakshetra is a 2.5D browser action RPG that tells the whole Mahabharata, from Bhishma's vow to the gates of heaven, across twelve chapters. You fight as Arjuna, Bhima, Yudhishthira and the twins, make moral choices that shape a five-virtue Dharma compass, and collect verses of the Bhagavad Gita along the way.

The entire game is a single self-contained `index.html`. All art is drawn procedurally on the canvas in the style of Pahari and Rajput miniature paintings, and all music and sound is synthesised live in the browser. There are no image or audio files.

- 12 chapters with boss fights, each boss beaten by a rule drawn from the epic
- 9 minigames, including the eye of the bird, the fish's eye, Ekalavya's practice, the Chakravyuha and Bhima's wrestling bout with Jarasandha
- 61 painted story scenes, lesson scrolls, a Gita codex and a skill system for each hero
- Progress is saved automatically in the browser

---

### Tech Stack

- **Canvas 2D API**: every character, background, story painting and effect is drawn in code
- **Web Audio API**: a synthesised raga soundtrack, instruments and sound effects
- **Web Speech API**: optional voice narration of the story
- **localStorage**: save data and settings
- **Google Fonts**: Yatra One and Cormorant Garamond

---

### Usage

Open `index.html` in any modern browser. Nothing needs to be installed or built.

To serve it locally instead:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

---

### Controls

| Key | Action |
|---|---|
| WASD or arrows | Move |
| J or left click | Main action: shoot, strike, loose an arrow |
| Hold K or right click | Charged attack |
| L | Close strike |
| U | Guard and parry |
| Shift | Roll, or steady your breath when aiming |
| Space | Jump |
| I | Special move or astra |
| Q | Switch special move |
| E | Swap between the twins |
| M or Esc | Menu |
| B / T | Journal / Skills |

---

<div align="center">

Built by [Shaurya Chopra](https://shauryachopra.dev/)

</div>
