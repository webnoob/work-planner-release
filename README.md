# Work Planner Mobile Releases

Welcome to the official release repository for **Work Planner** mobile updates.

This repository is used to publish over-the-air (OTA) bundle releases for the Work Planner app.  
It is intentionally lightweight and may contain release assets only (not full source code).

## What This Repo Is For

Each release here contains versioned mobile bundle assets used by the app updater:

- `mobile-bundle.zip` - the web bundle delivered to the app
- `mobile-manifest.json` - release metadata (version, channel, checksum, commit)
- `mobile-bundle.sha256` - integrity checksum

## Why It Exists

We separate release artifacts from the main application repository so updates are:

- Fast to distribute
- Easy to audit by version/tag
- Cost-efficient to host
- Reliable across staging and production channels

## Looking for Work Planner?

- Main website: [https://work-planner.co.uk](https://work-planner.co.uk)
- Main application repo: [https://github.com/webnoob/work-planner](https://github.com/webnoob/work-planner)

---

Built and published automatically via CI/CD from the main Work Planner codebase.
