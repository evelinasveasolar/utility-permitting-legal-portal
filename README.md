# Utility Permitting Legal Portal

Internal legal knowledge portal for environmental and planning case law relevant to utility-scale renewable-energy projects.

## Version

**v2.0.0 Stable**

## Current functionality

- Search and filtering
- Tag-based navigation
- Related judgments and trend overview
- Judgment editor beneath the ordinary detail view
- Unsaved-change indicator
- Reset changes
- Export of an updated `judgments.json`

## Publishing on GitHub Pages

Use:

- Source: **Deploy from a branch**
- Branch: **main**
- Folder: **/(root)**

## Updating data

After editing judgments in the portal:

1. Download the updated `judgments.json`.
2. Replace `data/judgments.json` in the repository.
3. Commit the change.

The static version does not save edits directly to GitHub or a shared database.
