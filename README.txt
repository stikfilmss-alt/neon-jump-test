NEON JUMP — PWA install notes

FILES
- index.html: website instructions + game
- manifest.json: app name, icon, and standalone display mode
- sw.js: offline cache
- icons/: Home Screen icons

PUBLISHING
1. Upload the contents of this folder to a static web host (for example GitHub Pages, Netlify, or your own HTTPS website).
2. Make sure the site is served over HTTPS.
3. Open the published URL in Safari on iPhone.
4. Tap Share -> Add to Home Screen -> Add.
5. Launch the Neon Jump icon from the Home Screen.

The website shows install instructions. When launched from the Home Screen, iOS standalone mode is detected and the game opens directly.

Note: iOS does not let a website silently add itself to the Home Screen. The user must confirm Add to Home Screen in Safari.
