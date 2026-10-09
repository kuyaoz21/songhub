SONGHUB DIGITAL SONGBOOK v1 — WINDOWS SETUP

1. Extract this ZIP into a folder.
2. Install Python from https://www.python.org/downloads/ (enable Add Python to PATH).
3. Open Command Prompt inside the extracted folder.
4. Run: py -m http.server 8000
5. Open http://localhost:8000 in Chrome on your Windows PC.

PUBLIC WEBSITE (free GitHub Pages)
1. Create a GitHub account at https://github.com.
2. Create a PUBLIC repository named songhub-songbook.
3. Upload index.html, style.css, app.js, songs.json, sw.js, manifest.webmanifest and icon.svg (not the ZIP).
4. Go to Settings > Pages > Build and deployment > Deploy from a branch > main > /(root) > Save.
5. Wait for GitHub to publish your HTTPS URL, usually https://YOURUSERNAME.github.io/songhub-songbook/.
6. Share that link. On iPhone, open it in Safari, tap Share > Add to Home Screen.

NOTES
- Offline mode works after a successful first visit and complete cache installation.
- Favorites are saved separately on each user's device.
- Songs were extracted automatically from a 384-page, two-column PDF. Verify data before sharing; wrapped lines and unusual formatting may cause errors.
- Check you have rights to republish the song list and use the SongHub name publicly.
- For updates replace songs.json and change the CACHE constant in sw.js, then republish.
- The app lists song numbers; it does not play or distribute karaoke audio/video.
