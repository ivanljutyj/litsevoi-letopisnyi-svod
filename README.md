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

| Book | Contents | Scans | Status |
|---|---|---|---|
| 1 | Biblical history | [archive.org](https://archive.org/details/lls1_20200717) | transcription running |
| 2 | Biblical history | archive.org (`lls2`) | queued |
| 3 | Biblical history | archive.org (`lls3`) | queued |
| 4 | Biblical history | archive.org (`lls4`) | queued |
| 5 | Troy | — | seeking scans |
| 6 | Alexander the Great | archive.org (`lls6`) | queued |
| 7 | Jewish War | — | seeking scans |
| 8–10 | Rome. Byzantium (87–967) | — | seeking scans |
| Rus volumes (Русь, Голицынский, Лаптевский, Царственная книга) | Russian history to 1567 | runivers / Актеон edition | queued |
