# Rally Chart: putting it online and installing it

This folder is the whole app. It needs a free web address so phones can install it.
GitHub Pages is free and permanent. Setup takes about 10 minutes, one time.

## 1. Put it online (GitHub Pages)

1. Go to github.com and create a free account (skip this if you have one).
2. Click the **+** in the top-right corner, then **New repository**.
3. Name it `rally-chart`, leave it **Public**, and click **Create repository**.
   (Public only means the app's code is visible. Your game data never leaves your phone.)
4. On the next page, click the **uploading an existing file** link.
5. Open this folder on your computer, select everything inside it
   (`index.html`, `manifest.webmanifest`, `sw.js`, `SETUP.md`, and the `icons` folder),
   and drag it all into the upload box. Then click **Commit changes**.
6. Go to the repository's **Settings** tab, then **Pages** in the left menu.
   Under "Branch," choose **main** and **/ (root)**, then click **Save**.
7. Wait a minute or two and refresh. GitHub shows your link at the top of that page:
   `https://YOUR-USERNAME.github.io/rally-chart/`

## 2. Install it on a phone or tablet

Open the link on the device, then:

- **iPhone / iPad (Safari):** tap the Share button, then **Add to Home Screen**, then **Add**.
- **Android (Chrome):** tap the ⋮ menu, then **Install app** (or **Add to Home screen**).

It now has its own icon, opens full screen, and works with no signal in the gym
after the first open. Send the link to anyone else who should have it.

## Updating the app later

1. Upload the new `index.html` to the repository (it replaces the old one).
2. Open `sw.js` on GitHub, click the pencil icon, change `rally-chart-v1` to `rally-chart-v2`
   (then v3, and so on each time), and commit.

Phones pick up the new version after the app has been opened once or twice with a signal.

## Good to know

- Each device keeps its own games. Use **Export** and **Import** to move a game between devices.
- Uninstalling the app or clearing the browser's site data erases that device's games,
  so export anything you want to keep first.
- The AI-written coaching notes only work from the Claude link. In the installed app,
  **Analyze** shows the plain stats summary. Everything else works the same.
