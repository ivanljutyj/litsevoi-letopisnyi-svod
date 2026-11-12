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

The goal is the complete chronicle — all volumes — translated into English
from the typed Russian translation.

Work runs on the three Учебник volumes of the Царская школа edition (the
illustrated translation edition, miniatures + typed Russian on every page):

| Volume | Pages | Status |
|---|---|---|
| Учебник 1 | 612 | in progress (OCR extraction feeds the translation run) |
| Учебник 2 | 742 | queued |
| Учебник 3 | 727 | queued |

After those, the remaining volumes of the edition, in mirror order:
Библейская история (Тома 1–4), Земная жизнь Иисуса Христа, Иудейская война
(2 книги), Рим. Византия 87–967 (6 книг), Русская летописная история
(Книги 1–23). Progress is tracked in the commit log — the translation runner
batch-commits every 25 pages.
