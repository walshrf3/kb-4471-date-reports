# kb-4471-date-reports

Support ticket #4471 merged 412 date reports as one bug. They hold two problems, filed here as issues:

1. Parser reads dates month first: 379 reports (5 read as a one-day move, footnoted)
2. `booking-v3` form hint says MM/DD/YYYY but reads day first: 33 reports

The kb page: `src/routes/kb/incidents/4471-split/+page.svx`. The page as the desk sees it: `rendered.html`.
