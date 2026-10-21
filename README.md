# Caught in the Web

A daily planner where each part of your life is a spider pulling on your web. Plan your hours so you hang in the middle.

## Put it on GitHub Pages

1. Sign in to GitHub and create a new repository (for example `caught-in-the-web`). On a free account it needs to be **Public** for Pages to work. Only the app's code is public; your plans and journal never leave your browser.
2. On the repository page, choose **Add file → Upload files**, drag in everything in this folder (`index.html`, `manifest.webmanifest`, `sw.js`, `README.md` and the `icons` folder), then **Commit changes**.
3. Go to **Settings → Pages**. Under *Build and deployment*, set Source to **Deploy from a branch**, Branch to **main** and folder **/ (root)**, then **Save**.
4. After a minute or two the page shows your address, like `https://YOUR-USERNAME.github.io/caught-in-the-web/`.

## Install it on your Android phone

1. Open that address in **Chrome**.
2. Tap the **⋮** menu → **Add to Home screen** (or **Install app**).
3. It now opens full screen from its own icon and works offline.

## Your data

Everything is saved in the browser you use, on that device. Your phone and your computer keep separate copies.

- To move your data, use **Your data → Download backup** at the bottom of the app on one device, then **Restore from backup** on the other.
- Download a backup now and then. Clearing your browser's site data erases what's stored there.

## Updating the app

Upload the new `index.html` over the old one. If the phone keeps showing the old version, close the app fully and reopen it. For a guaranteed refresh, also change `VERSION` at the top of `sw.js` (for example to `citw-v2`) and upload it.
