# Filerra

Filerra is a bilingual local file manager that runs entirely in the browser. It uses the File System Access API to manage real files and folders after the user explicitly selects a root folder and grants permission.

**Live app:** https://shadowur0.github.io/Filerra/

## Features

- English and Arabic interfaces with LTR and RTL support.
- Folder navigation, breadcrumbs, recent locations, and a folder tree.
- Create, rename, move, copy, cut, paste, and permanently delete items.
- Drag and drop within the app or from Windows Explorer.
- Multiple selection, search, sorting, grid view, and details view.
- Efficient local image thumbnails and a built-in image viewer.
- Per-folder automatic naming rules.
- Batch numbering based on selection order while preserving extensions.
- A self-contained `index.html` with no server or external libraries.

## Privacy

Filerra does not upload files. All file operations happen locally in the browser and are limited to folders the user explicitly authorizes. The browser may ask for permission again in a later session.

## Browser support

Use a recent version of Google Chrome or Microsoft Edge on Windows. GitHub Pages provides the secure HTTPS context required by the File System Access API.

> Deletion is permanent and does not use the Windows Recycle Bin. Filerra always asks for confirmation before deleting.

## Run locally

Download `index.html` and open it directly in Chrome or Edge, or use the live app linked above.

