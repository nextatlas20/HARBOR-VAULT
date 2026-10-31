# Harbor Vault Restore Staging

This repository records the offline qualification of municipal recovery snapshots.

<!-- RESTORE-WINDOW:BEGIN -->
## Restore window — cycle 42
Candidates: 15 physical | 10 valid | 5 invalid
Qualification: 4 eligible | 3 selected
Rejections: 2 status | 2 size | 2 hash

| Service | Selected candidate | Captured minute | Size bytes |
| --- | ---: | ---: | ---: |
| billing — Billing Ledger | RC-100 | 80 | 1200 |
| maps — Map Tile Index | RC-104 | 55 | 550 |
| radio — Radio Dispatch | RC-106 | 95 | 760 |
| water — Water Quality Archive | NONE | — | — |
<!-- RESTORE-WINDOW:END -->

## Controls

Candidate scans and the service catalog are sealed evidence. Promotion outputs are reviewed through independent Git branches.
