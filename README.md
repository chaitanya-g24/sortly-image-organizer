# Sortly — Open-source Image Organizer

A lightweight, browser-based image sorting website.

## Features
- Import an entire folder at once (folder picker) or multiple images with drag and drop
- Create collections and assign selected images
- Search by filename
- Sort by name, date, and file size
- Download selected images
- Export all images into collection folders in a ZIP
- No server, account, or image upload required

## Run locally
Open `index.html` in a modern browser. Click **Choose entire folder** and select a folder; the browser will provide its image files to the app. ZIP export loads JSZip from a CDN, so an internet connection is needed for that feature. All image previews and sorting happen locally in the browser.

## Privacy
Images are held in browser memory using local object URLs. Refreshing or closing the page clears the workspace. Export your organized ZIP before leaving.

## License
MIT. See `LICENSE`.
