# Лицевой летописный свод — Litsevoi letopisnyi svod

English translation of the Учебник edition of the Litsevoi letopisnyi svod —
the Facial Chronicle of Ivan the Terrible (1568–1576), the largest illustrated
chronicle of the Middle Ages. The Учебник edition of the Царская школа — three
volumes, the illustrated edition with typed Russian on every page — already
covers the complete chronicle, from the Creation to 1567. The goal is bounded:
translate those three volumes into English, page by page. Nothing more,
nothing less — no transcription of the manuscript hand.

## What is here

- `translations-en/` — the English translation, page by page
- `source-ru/` — the typed Russian translation each page is translated from

Source facsimiles are not stored in the repo: the complete Царская школа
edition (manuscript facsimile + typed Russian translation on each page) is
mirrored at [ivanon.xyz/library/svod/](https://ivanon.xyz/library/svod/), and
the raw Book 1 scan is on
[archive.org](https://archive.org/details/lls1_20200717).

## Method

Each page of the typed Russian translation is rendered into English by one
model (deepseek-v4.1-flash via OpenRouter, literary register, paragraphs and
section headers preserved). The manuscript facsimile printed alongside the
Russian on each page is the arbiter for anything ambiguous. The run is
resumable and batch-commits to GitHub every 25 pages.

## Sources

- Царская школа digital edition: [pravoslavnyy.ru](https://pravoslavnyy.ru/hristianstvo/pravoslavnie-knigi/lls/)
  (Актеон facsimile edition, 2008 — print run of 50 copies), mirrored at
  [ivanon.xyz/library/svod/](https://ivanon.xyz/library/svod/)
- Raw Book 1 facsimile: [archive.org](https://archive.org/details/lls1_20200717)
- Digitized editions: [runivers.ru](https://runivers.ru),
  [svod.ruvera.ru](https://svod.ruvera.ru)

## Scope

The project is exactly the three Учебник volumes — they cover the complete
chronicle, so that is the whole goal:

| Volume | Pages | Status |
|---|---|---|
| Учебник 1 | 612 | in progress (OCR extraction feeds the translation run) |
| Учебник 2 | 742 | queued |
| Учебник 3 | 727 | queued |

Progress is tracked in the commit log — the translation runner batch-commits
every 25 pages.
