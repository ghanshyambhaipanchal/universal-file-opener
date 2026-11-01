# Universal File Opener

A responsive, privacy-first file viewer for desktop and phone. File contents are selected and previewed in the browser and are never uploaded or saved online.

## Run

Open `index.html` in a modern browser, or serve this folder with any static file server. No build step, account, or external service is required.

## Features

- Select multiple files or drag and drop them into the workspace.
- Search and filter the local file list by type; sort by name or most recently added.
- Preview PDF, common images, plain text and code, JSON, CSV/TSV, audio, and video when supported by the browser.
- Download any file, remove it from the in-memory workspace, or use the browser open fallback for unsupported types.
- File contents stay local. Object URLs are released when removed or when the page is closed.

## Phone use

The interface adapts to phone screens with touch-friendly controls and swipeable file-type filters. Open the same `index.html` on your phone, or host this static folder on a web server reachable from your phone.

## Publish free with GitHub Pages

This project includes a GitHub Actions workflow for Pages. Put these files in a **public** GitHub repository named `universal-file-opener`, then in **Settings → Pages → Build and deployment**, choose **GitHub Actions** as the source. Pushes to `main` deploy the site automatically. The address will be `https://<your-github-username>.github.io/universal-file-opener/`; no purchased domain is needed. The repository source will also be public.

## Format limitations

A web app cannot natively open every proprietary or specialized format. Browser previews depend on available browser codecs and capabilities. Unsupported files can be downloaded and opened using a compatible app on the computer or phone.
