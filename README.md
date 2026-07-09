# command-center-v2-legal

Hosts the EULA and Privacy Policy for **Command Center**, served via GitHub Pages.

## Pages

| Page | Path | Description |
|---|---|---|
| Home | `/` | Landing page linking to all legal documents |
| EULA | `/eula.html` | End-User License Agreement |
| Privacy Policy | `/privacy.html` | Privacy Policy |

## GitHub Pages Setup

This repository uses plain HTML with no build step. GitHub Pages is configured to serve from the **`main` branch / root (`/`)** directory.

To enable GitHub Pages:
1. Go to **Settings → Pages** in this repository.
2. Under **Source**, select **Deploy from a branch**.
3. Choose **`main`** branch and **`/ (root)`** folder.
4. Click **Save**.

The site will be available at:
`https://eliteops-io.github.io/command-center-v2-legal/`

## Structure

```
.
├── index.html           # Landing page
├── eula.html            # End-User License Agreement
├── privacy.html         # Privacy Policy
├── assets/
│   └── css/
│       └── style.css    # Shared stylesheet
└── .nojekyll            # Disables Jekyll, serves plain HTML
```

## Updating Legal Content

Edit `eula.html` or `privacy.html` directly. Remember to update the **Effective Date** and **Last Updated** date in the document header when making material changes.
