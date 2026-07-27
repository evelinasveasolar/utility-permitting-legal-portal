# Utility Permitting Legal Portal

**Version 2.0.0 – Foundation**

Internal legal knowledge portal for Utility Permitting. Search, analyse and manage environmental and planning case law related to utility-scale renewable energy projects. Built as a static GitHub Pages application with a future migration path to a collaborative web application.

## Current functionality

- Search and advanced filtering
- Tag-based navigation
- Related and central judgments
- Judgment editor below the normal detail view
- In-memory change tracking
- Warning before leaving with unexported changes
- Reset changes
- Export a complete, validated `judgments.json`

## Publishing updates

1. Edit one or more judgments in the portal.
2. Click **Ladda ned judgments.json**.
3. Replace `data/judgments.json` in this repository.
4. Commit the change to GitHub.

Edits are not written directly to GitHub and disappear if the page is reloaded before export.

## Repository structure

```text
assets/
  company-logo.png
  company-logo-white.png
  header-background.jpg
  header-background.webp
data/
  judgments.json
js/
  app.js
styles/
  main.css
index.html
README.md
```

## GitHub Pages

Publish from the repository root on the main branch. No build step or framework is required.

## Future roadmap

- PDF upload and AI-assisted extraction
- Draft and publication workflow
- Authentication and role-based permissions
- Shared database and file storage
- Multi-user editing and version history
