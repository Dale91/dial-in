# Dial-In · Coffee Log

A small coffee dial-in app: log each shot (grind, grind time, dose, yield, shot time, tasting note), time shots with the built-in timer, switch between single and double, and save your best recipe for each bean.

It installs from a link (no App Store), works offline, and keeps each person's shots on their own phone.

## Put it online with GitHub Pages (free)

1. On github.com, create a new **public** repository, e.g. `dial-in`.
2. Upload everything in this folder, (all in one level, no folders):
   `index.html`, `manifest.webmanifest`, `sw.js`, and the four `.png` icons (README.md is optional).
   Easiest on a computer: **Add file → Upload files**, then drag the whole folder contents in.
3. In the repository, go to **Settings → Pages**. Under "Build and deployment", set **Source: Deploy from a branch**, **Branch: main**, folder **/ (root)**, and save.
4. After a minute or two your app is live at `https://YOUR-GITHUB-USERNAME.github.io/dial-in/`.

## Install it on a phone

- **iPhone:** open the link in **Safari** → Share → **Add to Home Screen**.
- **Android:** open the link in **Chrome** → ⋮ menu → **Install app** (or Add to Home screen).

It then opens full-screen like a normal app, and works without internet.

## Good to know

- Each person's data lives on **their own device**. Nobody can see anyone else's shots, and there's no account or server.
- Deleting the app from the home screen, or clearing browser data, deletes the shots. Use **Back up my data** (bottom of the app) now and then, and **Restore a backup** on a new phone.
- **Updating the app:** after you change `index.html`, also change `VERSION` in `sw.js` (e.g. `dialin-v2`) so phones pick up the new version.

## Gear & care

Add your espresso machine and grinder under **🛠 Gear & care**, then log cleans, backflushes, descales, water filters, burr cleans and services. Pick a **care level**: Relaxed, Standard or Proactive. Each job shows how often it's due at that level, when it was last done, and turns red once it's overdue. The machine and grinder marked **In use** are saved with every shot.

## Dial-in advice (free, no setup)

- **✨ Get dial-in advice** on any shot uses a built-in advisor that runs on the phone, offline and free. It reads the shot time, ratio, tasting note and your earlier shots of the same beans, then says which way to move the grind and by how many steps. It learns how many seconds one grind step changes your shots, and it also works out the grind time for your target dose.
- **Second opinion from your AI:** under the advice, tap **ChatGPT**, **Claude** or **Gemini**. The shot details are copied and that AI opens; ChatGPT and Claude usually fill the question in for you, otherwise just paste. **Copy** works with any other AI app.
