# Лицевой летописный свод — Litsevoi letopisnyi svod

English translation of the Litsevoi letopisnyi svod — the Facial Chronicle of
Ivan the Terrible (1568–1576), the largest illustrated chronicle of the Middle
Ages: 10 volumes, ~10,000 leaves, 16,000+ miniatures, covering history from
the Creation to 1567. The goal is translation only: the source text is the
typed modern Russian translation of the Царская школа edition, rendered into
English page by page.

## What is here

- `translations-en/` — the English translation, page by page
- `source-ru/` — the typed Russian translation each page is translated from
- `raw/` — the individual model outputs each page was produced from
- `conflicts/` — pages where the models disagree, kept for review
- `transcriptions/`, `translations/` — an early Book 1 pass from the raw
  facsimile, kept for reference

Source facsimiles are not stored in the repo: the complete Царская школа
edition (manuscript facsimile + typed Russian translation on each page) is
mirrored at [ivanon.xyz/library/svod/](https://ivanon.xyz/library/svod/), and
the raw Book 1 scan is on
[archive.org](https://archive.org/details/lls1_20200717).

## Method

Each page of the typed Russian translation is translated independently by two
frontier models (gemini-3.5-flash and gemini-4-carbon). Where the two
translations agree, the consensus text is kept; where they diverge, the fuller
reading is kept and the disagreement is preserved in `conflicts/` with both
readings for review. The manuscript facsimile printed alongside the Russian
on each page serves as the arbiter for anything ambiguous.

## Sources

- Царская школа digital edition: [pravoslavnyy.ru](https://pravoslavnyy.ru/hristianstvo/pravoslavnie-knigi/lls/)
  (Актеон facsimile edition, 2008 — print run of 50 copies), mirrored at
  [ivanon.xyz/library/svod/](https://ivanon.xyz/library/svod/)
- Raw Book 1 facsimile: [archive.org](https://archive.org/details/lls1_20200717)
- Digitized editions: [runivers.ru](https://runivers.ru),
  [svod.ruvera.ru](https://svod.ruvera.ru)

## Scope

The goal is the complete chronicle — all volumes — translated into English
from the typed Russian translation on this repo:

| Book | Contents | Status |
|---|---|---|
| 1 | Biblical history | translation running |
| 2–4 | Biblical history | queued |
| 5 | Troy | queued |
| 6 | Alexander the Great | queued |
| 7 | Jewish War | queued |
| 8–10 | Rome. Byzantium (87–967) | queued |
| Русская летописная история, Книги 1–23 | Russian history to 1567 | queued |
