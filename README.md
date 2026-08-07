# Wortschatz — Dein Weg zu C2 🇩🇪

A free, open-source German trainer that runs entirely in your browser — from your first
„Hallo“ to near-native C2. No account, no server, no tracking: your progress lives in
your browser's local storage.

**[▶ Use it here](https://jeelswami.github.io/wortschatz-trainer/)**

## What's inside

| Tab | What it does |
|---|---|
| **Lernen** | Daily spaced-repetition session: due reviews + new cards from *your* level |
| **Wörterbuch** | Browse/search 1,000+ cards; filter by level (A1–C2), word type and topic; add your own |
| **Grammatik** | The complete A1→C2 grammar spine in 38 compact topics with tables, examples and common-mistake warnings |
| **Test** | Einstufungstest: 30 questions that place you between A1 and C2 and point you at your gaps |
| **Fortschritt** | Streak, mastery stats, per-level progress, backup export/import |
| **Fahrplan** | A phased long-term strategy to C1/C2 with tickable milestones |
| **Hilfe** | How everything works, incl. the science behind the method |

## The deck (1,000+ cards, A1→C2)

- **Nouns are color-coded by gender** — der (blue), die (red), das (green) — always with plural.
- **Verbs show the three Stammformen** — *stiehlt · stahl · hat gestohlen* = er/sie/es-**Präsens** · **Präteritum** · **Perfekt** (with its haben/sein auxiliary). From these three forms you can build all six German tenses — the Hilfe tab shows how.
- **Prepositions + case are part of the card** (*sich bewerben um + Akk*), as are separable-prefix markers and register warnings.
- **Chunks are first-class**: Funktionsverbgefüge (*in Kraft treten*), idioms (*die Kirche im Dorf lassen*), and exam connectors.
- **Topic decks**: Alltagsdeutsch (how Germans actually talk — *krass, Bock haben, Feierabend*), Studium (university life), Beruf (office & contracts), Forschung (academic German).
- Every single card carries a natural German example sentence **with English translation**, and many carry mnemonic hooks (etymology, literal images).

## Levels & sources

Levels follow the CEFR. A1–B1 vocabulary is aligned with the official Goethe-Institut
Wortlisten and mined from real course material (Netzwerk-family A1–B1.1); B2–C2 follows
Goethe/telc exam-preparation conventions and frequency in edited German (quality press,
academic prose). All content went through independent proofreading passes before release.

## The method (why it works)

Spaced repetition (spacing effect), active recall before flipping (testing effect),
production practice via the EN→DE mode (generation effect), gender colors and idiom
images (dual coding), collocation cards (chunking), and mixed sessions (interleaving).
Details and references in the app's Hilfe tab.

## Running locally

It is a single HTML file. Clone and open:

```bash
git clone https://github.com/JeelSwami/wortschatz-trainer.git
open wortschatz-trainer/index.html
```

## Contributing

Found a wrong article, plural, verb form, or an unnatural example? Open an issue or PR —
correctness is the whole point. New cards are welcome if they follow the card format
(gender + plural for nouns, three forms + auxiliary for verbs, preposition + case,
example sentence with translation).

## Acknowledgements & references

- **Goethe-Institut** — the official [A1](https://www.goethe.de/pro/relaunch/prf/de/A1_SD1_Wortliste_02.pdf), [A2](https://www.goethe.de/pro/relaunch/prf/en/Goethe-Zertifikat_A2_Wortliste.pdf) and [B1](https://www.goethe.de/pro/relaunch/prf/de/Goethe-Zertifikat_B1_Wortliste.pdf) Wortlisten (the B1 list jointly with ÖSD and Universität Freiburg/Schweiz) were used to verify level assignments. A telc course vocabulary list served as cross-reference. This project is **not** affiliated with or endorsed by the Goethe-Institut, ÖSD or telc gGmbH.
- **Language standards** — genders, plurals, verb forms and orthography follow Duden conventions. All example sentences, definitions and mnemonics are original; no textbook or dictionary content is reproduced.
- **Learning science** — Ebbinghaus, *Über das Gedächtnis* (1885); Roediger & Karpicke, "Test-Enhanced Learning", *Psychological Science* (2006); Cepeda et al., "Distributed Practice in Verbal Recall Tasks", *Psychological Bulletin* (2006); Paivio's dual-coding theory. The scheduler is a simplified SM-2 variant (Woźniak/SuperMemo), in the tradition of Leitner's box system.
- **Curriculum shape** — follows the CEFR (Council of Europe); topic coverage informed by modern German coursebook curricula.
- **Tooling** — designed and developed with the assistance of Claude (Anthropic); every card, grammar topic and test question passed independent proofreading and adversarial answer-verification before release.

## Privacy & ethics

No account, no cookies, no analytics, no tracking. All data stays in your browser's
local storage. The placement test is a self-assessment aid, not a certificate — for an
official CEFR certificate, take a Goethe/telc/ÖSD exam.

## License

MIT — learn freely.
