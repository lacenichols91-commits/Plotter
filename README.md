# Plotter — free website prototype

This is a first interactive front-end prototype for Plotter, an author planning and drafting workspace.

## Run it
1. Extract `plotter-website.zip`.
2. Open `index.html` in a modern browser (Chrome or Edge recommended).

## Current prototype features
- Draft editor with font selector, bold, italic, underline, lists, undo/redo controls
- Browser-local autosave
- Scene, plot, character, setting/worldbuilding, research-note and sticky-note tabs
- Word counts and editable word/editing goals
- Themes and background colour preferences
- Export draft to TXT or HTML, project entries to CSV, or a JSON backup

## Important limitations
This is a prototype, not yet a secure, production-ready writing service.
- Data is stored in the browser's local storage on this device. It does not sync across devices and may be lost if browser storage is cleared.
- There is no real login/account system yet.
- Offline use depends on the file being available locally; this first version is not yet a fully installable offline PWA.
- PDF, DOCX, DOC, XLSX, RTF, EPUB and MOBI export are not implemented in this first prototype.
- Do not store confidential manuscripts here until authentication, secure server-side storage, backups, and privacy/security review are implemented.

## Publish free with GitHub Pages
1. Create or sign in to a GitHub account.
2. Create a new public repository named `plotter`.
3. Upload `index.html` to the repository's root.
4. Open repository **Settings → Pages**.
5. Under build/deployment, choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
6. Wait for GitHub Pages to publish. Your site address will look like `https://YOUR-USERNAME.github.io/plotter/`.

GitHub's interface may change. A public repository means the website source code is public; do not upload private manuscripts or secrets to the repository.
