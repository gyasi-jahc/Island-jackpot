# Island Jackpot

A free-to-play Caribbean-inspired mobile arcade. It is a static website: no build step, accounts, server, paid assets, or external libraries are required.

## What is included

- Seven playable original games: Palm Tree Slots, Reef Roulette, Calypso 21, Coconut Toss, Limbo Lights, Soca Spin, and Treasure Tide.
- Virtual coins saved in the browser, plus a once-per-day free 250-coin bonus.
- Two original generated music styles (Sunset groove and Carnival pulse), created locally with the Web Audio API.
- Responsive mobile layout, accessibility labels, sound controls, and an offline-capable service worker when hosted over HTTPS.
- No real-money betting, purchases, cash prizes, or redemption. The GYASI credit is intentionally subtle.

## Run it for free

### Quick local preview

1. Download this repository: click **Code → Download ZIP** on GitHub, then unzip it.
2. Open `index.html` in a current browser. The games work; browser security may prevent the offline-install feature and background music from being fully available when opened as a local file.

### Recommended local preview with VS Code

1. Install the free [Visual Studio Code](https://code.visualstudio.com/) editor.
2. Open the unzipped `Island-jackpot` folder in VS Code.
3. Install the free **Live Server** extension from the Extensions panel.
4. Right-click `index.html` and choose **Open with Live Server**. The browser will open the app locally.

### Free public hosting with GitHub Pages

1. Open this repository on GitHub and select **Settings → Pages**.
2. Under **Build and deployment**, choose **Deploy from a branch**.
3. Select the `main` branch and `/ (root)` folder, then click **Save**.
4. Wait for GitHub Pages to publish. The Pages settings screen will show the public URL. Open it on your phone and use the browser's **Add to Home Screen** option.

GitHub Pages is a static host; no build command is needed. The service worker requires HTTPS, which GitHub Pages provides.

## Make changes

- Edit `index.html` for the games, text, colors, layout, and music behaviors.
- Edit `manifest.webmanifest` for the app name and install appearance.
- Edit `sw.js` when adding files so the offline cache includes them.
- Commit and push your changes; GitHub Pages will publish the update automatically.

## Notes

The coins are local browser data and can be reset by clearing this site's storage. They have no monetary value. The audio is synthesized in the browser; it does not use copyrighted recordings. Browser audio generally starts only after a button tap. This project is a casual entertainment demo, not gambling software.
