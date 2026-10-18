# Oahu Home Base (PWA)

Files:
- index.html: the app
- manifest.json: name, icons, colors for the home screen
- sw.js: offline cache (bump VERSION to ship updates)
- icons/: app icons (192, 512, maskable 512, 180 Apple touch, 32 favicon)
- .nojekyll: tells GitHub Pages to serve files as-is

## Ship an update
1. Edit index.html (or anything else).
2. Open sw.js and change `const VERSION = "v1";` to the next number ("v2", "v3", ...).
3. Commit and push (or upload the changed files on github.com).
4. On your phone, open the app, close it fully, and open it again. It reloads itself onto the new version.
