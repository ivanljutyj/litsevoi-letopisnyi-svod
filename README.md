# Лицевой летописный свод — Litsevoi letopisnyi svod

Transcription and English translation of **Book 1 (Библейская история / Biblical
history)** of the Litsevoi letopisnyi svod — the Facial Chronicle of Ivan the
Terrible (1568–1576), the largest illustrated chronicle of the Middle Ages:
10 volumes, ~10,000 leaves, 16,000+ miniatures, covering history from the Creation
to 1567. No typed text of this manuscript has ever been published.

## What is here

- `transcriptions/` — Book 1, page by page, in Church Slavonic (diplomatic
  transcription from the 16th-century semi-ustav hand)
- `translations/` — the same pages in English
- `raw/` — the individual model outputs each page was produced from
- `conflicts/` — pages where the models disagree, kept for review
- `lls1.pdf` — the source facsimile (508 pages), also hosted at
  [ivanon.xyz/library/lls1.pdf](https://ivanon.xyz/library/lls1.pdf)

## Method

Each page is transcribed independently by two frontier vision models
(gemini-3.5-flash and gemini-4-carbon). Where the two transcriptions agree,
the consensus text is kept; where they diverge, the fuller reading is kept and
the disagreement is preserved in `conflicts/` with both readings for review.
The biblical narrative portions align with the Church Slavonic Bible, which
serves as a check on the transcription.

## Sources

- Facsimile scans: [archive.org](https://archive.org/details/lls1_20200717)
  (from the Актеон facsimile edition, 2008 — print run of 50 copies)
- Digitized editions: [runivers.ru](https://runivers.ru),
  [svod.ruvera.ru](https://svod.ruvera.ru)

## Scope

The goal is the complete chronicle — all volumes — transcribed and translated
into English on this repo. In progress:

All volumes are available in the Царская школа digital edition
([pravoslavnyy.ru](https://pravoslavnyy.ru/hristianstvo/pravoslavnie-knigi/lls/)),
which typesets a modern Russian translation alongside each manuscript page.
Mirrored at [ivanon.xyz/library/svod/](https://ivanon.xyz/library/svod/).
The compact modern-Russian rendering ("History Textbook", Учебник) used as the
translation source here was compiled by N. P. Pokarev, A. B. Yanovsky and
K. A. Babkin — the English translation in this repo is a translation of their
Russian text.
The Slavonic transcription (the manuscript hand itself) has never been typed
anywhere — that is what this repo produces.

| Book | Contents | Status |
|---|---|---|
| 1 | Biblical history | transcription running |
| 2–4 | Biblical history | queued |
| 5 | Troy | queued |
| 6 | Alexander the Great | queued |
| 7 | Jewish War | queued |
| 8–10 | Rome. Byzantium (87–967) | queued |
| Русская летописная история, Книги 1–23 | Russian history to 1567 | queued |
