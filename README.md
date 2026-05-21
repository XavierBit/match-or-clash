# Match or Clash

A timed classroom vocabulary game for English language learners, built as a single self-contained HTML file. Designed for screenshare use in online classes at EASY Escola de Idiomas.

## How it works

A word appears on screen. Students call out the answer. The teacher clicks the correct option. The timer runs down. Simple.

Three game modes:

- **Antonyms** — find the opposite
- **Synonyms** — find the match
- **Mixed** — both types, randomly combined

## Levels

| Level | Status |
|-------|--------|
| A1 | Available |
| A2 | Available |
| B1 | Available |
| B2 | Available |
| C1 | Available |

Word lists are fully editable via the built-in editor. Each level can be expanded with the batch import or JSON import tools.

## Setup

No installation. No dependencies. No internet connection required during gameplay (font loads from Google Fonts on first open).

1. Download `match-or-clash.html` and `Easy Logo 2023 new.png`
2. Keep both files in the same folder
3. Open `match-or-clash.html` in any modern browser

## Word list files

The `word-lists/` folder contains one JSON file per level. To load a word list:

1. Open the game and click **Edit** on the target level
2. Select the **Antonyms** or **Synonyms** tab
3. Click **Import JSON** and pick the corresponding file
4. Repeat for the other tab
5. The pairs are saved automatically to the browser

## Settings

- **Timer**: 30s / 60s / 90s / 2 min
- **Stats screen**: toggle on/off — when off, the game freezes at time-up and a "See Results" button appears, useful for class discussion before moving on
- **Save progress**: saves your position to resume in a later session

## Customising word lists

Use the built-in editor to add, remove, or edit pairs. For bulk additions use **Batch import** (one pair per line, separated by `|`) or **Import JSON**.

JSON format:

```json
{
  "antonyms": [
    ["word", "opposite"],
    ["ancient", "modern"]
  ],
  "synonyms": [
    ["word", "synonym"],
    ["brave", "courageous"]
  ]
}
```

## Part of the EASY Classroom Tools suite

- [Would You Rather](https://github.com/XavierBit/would_you_rather)
- Match or Clash (this repo)

---

Made with ❤️ for the students of EASY Escola de Idiomas, Brazil.
