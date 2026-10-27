# SHASHANK.MUSICPLAYER

A static, responsive browser-based audio player with a Web Audio API equalizer and experimental center-channel/vocal-focus effect.

## Run locally
1. Extract the ZIP.
2. Open `index.html` in a modern browser (Chrome or Edge recommended).
3. Choose an audio file you have permission to use.
4. Press Play, then try the equalizer and sound profiles.

For best compatibility, serve it locally instead of opening the file directly:
- Install Python 3
- Open a terminal in this folder
- Run: `python -m http.server 8000`
- Visit `http://localhost:8000`

## Deploy free with GitHub Pages
1. Create a GitHub repository named `shashank-musicplayer` (public).
2. Upload `index.html` and `README.md` to the repository root.
3. Open repository Settings -> Pages.
4. Under Build and deployment, choose "Deploy from a branch".
5. Select `main` and `/ (root)`, then Save.
6. Wait for deployment. Your URL will look like:
   `https://YOUR-GITHUB-USERNAME.github.io/shashank-musicplayer/`
7. Open that public HTTPS link and share it with friends.

Alternative: deploy the folder with Netlify Drop or Cloudflare Pages.

## Important technical limits
- This page does not include or run FxSound's native Windows DSP engine or virtual driver.
- The equalizer works on user-selected local audio in the browser.
- Vocal Focus is a simple experimental stereo center-channel mix, not AI source separation. It will not cleanly isolate vocals on every track.
- Spotify is linked separately. Spotify's platform rules prohibit altering Spotify audio streams, so this page does not process Spotify playback.
- Do not upload or redistribute copyrighted music without permission.
- If you incorporate code from FxSound's repository, review and comply with its AGPL-3.0 license and applicable notices.
