# ECOC 2026 Programme (unofficial mirror)

Static, self-contained viewers for the ECOC 2026 conference programme, built so
the schedule is usable on a phone or tablet during the conference.

Three views, all single HTML files with the programme data embedded — no server,
no network needed once loaded:

| File | View |
|---|---|
| `programme.html` | Searchable vertical list |
| `talk-grid.html` | Room x time grid, one block per talk |
| `sessions-grid.html` | Room x time grid, one block per session |

Data scraped 2026-09-21 from the [official programme](https://ecoc2026.org/site/programme/?a=ecoc2026).
Paper PDFs are not included here; the PDF links point back to the official site.

Pages carry `noindex` and the site ships a `robots.txt` disallowing crawlers.

Generator scripts (`scrape_programme.py`, `build_*.py`, `download_pdfs.py`) live
outside this repo.
