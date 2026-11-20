NIGHTCITY TERMINAL v0.5 — PWA package

FILES
- index.html: complete app and simulated terminal
- manifest.webmanifest: installable app metadata
- sw.js: offline cache
- icon.svg: app icon

PUBLISH FREE WITH GITHUB PAGES
1. Create or open a GitHub repository.
2. Upload all four files to the repository root (not inside a subfolder).
3. Open repository Settings > Pages.
4. Under Build and deployment choose Deploy from a branch.
5. Select branch main and folder /(root), then Save.
6. Wait for the Pages URL, then open it in Safari on iPhone.
7. Safari Share > Add to Home Screen > Add.

FEATURES
- Simulated shell and virtual file system
- pwd, ls, cd, cat, touch, mkdir, echo, grep, find
- sort, uniq, cut, limited awk example, export, printenv, env, ps
- Pipes, command history, 8 guided missions, hints, XP and levels
- Local browser storage is not used in this version; progress is held for the current session.

LIMITATIONS
This is not a real Linux kernel or full Bash. Commands are simulated in JavaScript.
No real process execution, package installation, SSH, network scanning, or access to iPhone files.
A real Ubuntu backend would require a separate server/container service and secure authentication.
