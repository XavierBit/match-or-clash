# Match or Clash 🎮
### A Classroom Word Relationship Game for English Teachers
###### Download the .html game file and the logo from: https://github.com/XavierBit/match-or-clash/releases

<img width="762" height="auto" alt="Match-Or-Clash" src="https://github.com/user-attachments/assets/36f03a50-5fb6-4947-b554-5f173d13f7b1" />


A self-contained, single-file web app designed for online and in-person English classes. Display it on a shared screen (e.g. via Jitsi screenshare) and challenge your students to match or clash words against the clock.

---

## How It Works

A word appears on screen asking for a synonym or antonym. Students call out the answer. 
The teacher clicks the correct option. The timer runs down and a statistic shows how many the students got right.

<img width="762" height="auto" alt="game" src="https://github.com/user-attachments/assets/253d22df-a4eb-410f-8fbb-d8af12cf0b00" />


Three game modes:

- **Antonyms** — find the opposite
- **Synonyms** — find the match
- **Mixed** — both types, randomly combined

Five levels, all pre-loaded with word pairs:

| Level | Name |
|-------|------|
| A1 | Beginner |
| A2 | Elementary |
| B1 | Intermediate |
| B2 | Upper-Intermediate |
| C1 | Advanced |

---

## Features

- 50 antonym + 50 synonym pairs at B1, 25 pairs per type at all other levels.
- Timed rounds: 30s, 60s, 90s, or 2 min
- Streak tracker and live score display
- Colour-coded prompts — OPPOSITE in red, SYNONYM in teal
- Stats screen toggle — freeze the game at time-up for class discussion before revealing results
- Save and resume progress across sessions
- Full word list editor with batch import and JSON import
- Additional word pairs available
- Works in any modern browser — just open the file

---

## How to Use

1. Download [match-or-clash.html](https://github.com/XavierBit/match-or-clash/releases/) and [Easy Logo 2023 new.png](https://github.com/XavierBit/match-or-clash/releases/) — keep both in the same folder 
2. If you don't want to use our logo, just swap it out with your own.
3. Open `match-or-clash.html` in any modern browser
4. Choose a mode, a level, and set the timer
5. Screenshare with your students
6. Students call out the answer — you click it
7. Hit Play Again or change settings between rounds

## You can play the game online too!

Go to [ to play online. ](https://xavierbit.github.io/match-or-clash/match-or-clash.html) 
All functions are available — changes are stored only in your browser.

---

## Editing Word Lists

Click **Edit** on any level card to open the word list editor. From there you can:

- Edit any existing pair
- Add new pairs one by one
- Delete pairs you do not want
- Use **Batch import** — one pair per line, separated by `|`
- Use **Import JSON** to load a full word list file directly
- **Reset** a tab back to its defaults at any time

Custom word lists are saved in the browser's local storage and persist between sessions.

<img width="762" height="auto" alt="settings" src="https://github.com/user-attachments/assets/5b75a5c1-53cf-47c0-b37b-48bb79426426" />

<img width="762" height="auto" alt="settings_II" src="https://github.com/user-attachments/assets/097d8184-dc8a-4041-a375-c6d4fc1dd9ff" />

### JSON format

```json
{
  "antonyms": [
    ["ancient", "modern"],
    ["guilty", "innocent"]
  ],
  "synonyms": [
    ["brave", "courageous"],
    ["wealthy", "rich"]
  ]
}
```

The `word-lists/` folder in this repo contains ready-made JSON files for all five levels.

---

## Settings

- **Timer** — 30s / 60s / 90s / 2 min, set before each round
- **Stats screen** — when on, navigates to the results screen automatically at time-up; when off, the game freezes and a See Results button appears — useful for discussing the last question before moving on
- **Save progress** — saves your current position so you can resume in a later session; Reset progress clears this without affecting your word lists


---

## Classroom Tips

- The 60s timer works well as a warm-up; 90s or 2 min suits a main activity
- Mixed mode works best once students are comfortable with both types separately
- When stats screen is off, use the frozen last question as a discussion prompt before revealing results
- Use the streak dots to spot runs of correct answers and celebrate them
- JSON files make it easy to share custom word lists with other teachers

---

## Technical Notes

- Single `.html` file plus one logo `.png` — no other dependencies
- Font (Outfit) loads from Google Fonts on first open; not required after that
- Word lists and progress stored in `localStorage` — tied to the browser and machine
- Use Import/Export to move word lists between machines or share with colleagues

---

## Version History

| Version | Changes |
|---------|---------|
| v1.0 | Initial release — all five levels, antonyms and synonyms, JSON import, stats toggle, save/resume |
| v1.1 | Added out of the box examples for all levels |

---

## License

GNU General Public License v3.0 - https://www.gnu.org/licenses/gpl-3.0.en.html

Copyright (C) 2025 Ivo Schmid / EASY Escola de Idiomas

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License as published by the Free Software Foundation, either version 3 of the License, or (at your option) any later version.

---

## Part of the EASY Classroom Tools Suite

This game is part of a growing collection of interactive classroom tools developed for [EASY Escola de Idiomas](https://github.com/XavierBit).

- [Would You Rather](https://github.com/XavierBit/would_you_rather)
- [Deal or No Deal](https://github.com/XavierBit/deal-or-no-deal)
- [Match or Clash](https://github.com/XavierBit/match-or-clash) (this repo)

***Made with ❤️ for the students of EASY Escola de Idiomas, Brazil.***
