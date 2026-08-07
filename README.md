# Wortschatz — Dein Weg zu C1 🇩🇪

A free, open-source German vocabulary trainer that runs entirely in your browser.
No account, no server, no tracking — your progress lives in your browser's local storage.

**[▶ Use it here](https://jeelswami.github.io/wortschatz-trainer/)**

## Why this exists

Most flashcard apps let you learn German words the wrong way: without the article,
without the plural, without the verb forms, without the preposition. This trainer
bakes the right habits in:

- **Nouns are color-coded by gender** — <ins>der</ins> (blue), <ins>die</ins> (red), <ins>das</ins> (green) — and always carry their plural.
- **Verbs always show their three key forms** (*gibt · gab · hat gegeben*) and their fixed preposition + case (*sich bewerben **um + Akk***).
- **Chunks, not just words** — idioms and collocations (*eine Entscheidung treffen, in Betracht ziehen*) are first-class cards.
- **Spaced repetition** (simplified SM-2): cards you struggle with come back sooner, cards you know come back in weeks.

## Features

- 680-card curated deck from A1 to C1, built from real course material — every card with an example sentence and English translation
- Both directions: German → English and English → German (with cloze hints)
- **Hinweis** button: see the word in a real example sentence before you answer
- **Grammatik** tab: the A1→C1 grammar spine in 31 compact topics with examples and common-mistake warnings
- **Fahrplan** tab: a phased study roadmap to C1/C2 with progress checklists
- Add your own cards (mined from your own reading) — stored locally
- Streak tracking, per-level progress, 14-day activity chart
- Export / import your progress as JSON
- Light & dark theme, keyboard-first (Space = flip, 1–4 = grade, H = hint)

## Running locally

It is a single HTML file. Clone and open:

```bash
git clone https://github.com/JeelSwami/wortschatz-trainer.git
open wortschatz-trainer/index.html
```

## Contributing

Found a wrong article, a bad plural, a mistranslation? Please open an issue or PR —
correctness is the whole point. New vocabulary PRs are welcome if entries follow the
card format (article, plural, verb forms, preposition, example sentence with translation).

## License

MIT — learn freely.
