DuitTrack v0.10.0 — iPhone/Android Home Screen web app (test version)

FILES (upload ALL of them, keep the folder layout):
  index.html, manifest.webmanifest, sw.js, icons/ (4 png files)

HOST FREE ON GITHUB PAGES (no coding)
 1. github.com → + (top right) → New repository
    Name: duittrack   ·   Public   ·   Create repository
 2. Click "uploading an existing file" → drag in index.html, manifest.webmanifest, sw.js
    and the icons folder → Commit changes
 3. Settings → Pages → Source: "Deploy from a branch" → Branch: main, folder: / (root) → Save
 4. Wait 1–2 minutes. Your link: https://<your-github-username>.github.io/duittrack/

INSTALL ON IPHONE
  Open the link in SAFARI → Share button → "Add to Home Screen" → Add.
  Open it from the new DuitTrack icon (not from Safari) for the full-screen app.

INSTALL ON ANDROID
  Open the link in Chrome → ⋮ menu → "Add to Home screen" / "Install app".

UPDATING TO A NEW VERSION
  Upload the new files over the old ones (same names). In sw.js, change VERSION
  (e.g. duittrack-0.11.0). Testers: close the app fully and open it again.
  Their data stays.

NOTES
  - Data is saved on each phone only. Deleting the Home Screen icon on iPhone
    also deletes its data.
  - Works offline after the first open.
  - Exchange rate auto-fill and receipt reading need internet.
  - The repo is public, so anyone with the link can see the mockup code.
