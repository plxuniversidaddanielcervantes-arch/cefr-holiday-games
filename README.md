# CEFR Holiday Vocab Games 🎃🎄

Interactive, classroom-ready vocabulary games for English learners at every CEFR level (A1–C2), in two holiday themes: **Halloween** and **Christmas**.

Each edition contains four mini-games — **Memory**, **Word Search**, **Crossword**, and a word-guessing game (Hangman / Snowman) — and three difficulty levels per game.

## Files

| File | Contents |
|---|---|
| `index.html` | Landing page linking to both editions |
| `halloween-cefr-games.html` | 🎃 Halloween edition: Memory, Word Search, Crossword, Hangman |
| `christmas-cefr-games.html` | 🎄 Christmas edition: Memory, Word Search, Crossword, Snowman word game |

## CEFR levels

Each level uses 12 themed words with an emoji icon and a definition clue:

- **A1 Beginner** — simple nouns (ghost, pumpkin…)
- **A2 Elementary** — compound words (black cat, jack-o'-lantern…)
- **B1 Intermediate** — descriptive words (spooky, haunted…)
- **B2 Upper-Intermediate** — precise words (eerie, supernatural…)
- **C1 Advanced** — sophisticated words (macabre, ominous…)
- **C2 Mastery** — rare / literary words (specter, wraith, sepulchral…)

## Play offline

Every game is a **single self-contained HTML file**: no images, audio, fonts, libraries, or internet connection required. Double-click the file to open it in any modern browser (Chrome, Edge, Firefox, Safari). Works on laptops, tablets, and interactive whiteboards.

## Playing online (GitHub Pages)

This repository is published with GitHub Pages:

1. Push all files to the `main` branch.
2. Repository **Settings → Pages → Source: Deploy from a branch → `main` / `(root)**.
3. The site is live at `https://<your-username>.github.io/<repository-name>/` shortly after saving.

## For teachers

- Difficulty 1–3 adjusts word count and board size for mixed-level classes.
- Hints reveal the first letter of a missing word; check answers inside each game.
- To customize, edit the `VOCAB` object at the top of each game script — keep the `word` field uppercase with no spaces, e.g. `BLACKCAT`.
- Free for classroom use.
