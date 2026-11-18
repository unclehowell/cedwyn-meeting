# Public Authorities & Council Chamber — 22 October 2026

This repository is the standalone source archive for the **Llandough Community Council meeting of 22 October 2026**, published as part of BucklerFamily.estate.

## Current live deployment

**Live route:** [https://bucklerfamily.estate/meeting/](https://bucklerfamily.estate/meeting/)

As verified in the repository/deployment audit on 7 November 2026, the live route is still assembled from the separate `unclehowell/cedwyn` repository, branch `2026-10-22`, directory `static/2026-10-22/`. This repository is therefore a separate Git repository and working source copy, but it is **not yet the production deployment source**. Do not describe a commit to this repository as a live-site update unless the deployment configuration and the served output have both been verified.

The path mapping matters: files under `static/2026-10-22/` are served at the route root `/meeting/`. For example, `static/2026-10-22/data/central.json` maps to `/meeting/data/central.json`, not `/meeting/2026-10-22/data/central.json`.

## Repository contents

- **Meeting snapshot:** `static/2026-10-22/` — the dated meeting page and its supporting public materials.
- **Historical site generations:** `blog/`, `evidence-catalogue/`, `db-data.js` and the root `index.html` are retained as legacy material. They are not the current live route according to the 7 November deployment audit.
- **Working papers:** the root contains dated case/strategy working files from an earlier site workflow. They are not part of the live meeting page. Their continued presence in this public repository requires an owner-led privacy and scope review; they have not been deleted or rewritten by this documentation change.
- **Deployment and data sync:** inspect `.github/`, `SPLIT.json` and `tools/` before changing hosting. The page's central-catalogue data is a derived, read-only cache; the central catalogue remains the source of truth.

## Evidence and editorial safeguards

The page records correspondence, the Council meeting, and the subsequent administrative history. It must distinguish the requester's account and proposals from Council wording, draft minutes from approved minutes, acknowledgements from substantive replies, and each information-request route from the others. Keep personal contact details and private correspondence out of the public page. Do not treat an expected consideration date as a promised reply date.

The material is a public-interest research record, not a finding of wrongdoing or a request for the Council to determine land ownership.

## Rights and licence

© Williams–Buckler family. All rights reserved. Licence terms apply.

The content and original code in this repository are not open source. You may read it, link to it and quote it fairly with credit. Any other copying, adaptation or commercial use (books, film, TV, documentary, podcasts, paid articles, AI training) needs a written licence first. Full terms: https://bucklerfamily.estate/licence/ · Apply: https://bucklerfamily.estate/enquire/ · See `LICENSE` and `NOTICE`. Third-party components keep their own licences.
