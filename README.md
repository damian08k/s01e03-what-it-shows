# S01E03 · what it shows

This repository contains the signed KB page for ticket #4471 and a static HTML preview of how that page reads in the support KB.

The page summarizes the exported reports by the cause rules in the supplied KB code. It counts report IDs once: 427 export rows reduce to 412 unique reports after removing 15 repeated rows. The raw export is not included in this public deliverable.

The repository is intended to have these two GitHub issues:

1. `Date parser assumes month-first for day-first tenant locales (379 reports)`
2. `Booking-v3 date hint conflicts with day-first tenants (33 reports)`

The rendered preview is at [`rendered/kb/incidents/4471/index.html`](rendered/kb/incidents/4471/index.html).
