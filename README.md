# Five Clues: setup

Five Clues is an installable web app. It works offline once installed and updates itself when you replace the data files.

## Put it online for free with GitHub Pages (about 5 minutes)

1. Create a free account at github.com if you don't have one.
2. Click **+** (top right), then **New repository**. Name it `five-clues`, set it to **Public**, and click **Create repository**.
3. On the new repository page, click **uploading an existing file**.
4. Unzip `five-clues-app.zip` on your computer. Drag everything inside the folder (`index.html`, `dx.js`, `rx.js`, `sw.js`, `manifest.webmanifest`, `README.md` and the `icons` folder) into the upload area. Upload the contents, not the folder itself. Click **Commit changes**.
5. Go to **Settings**, then **Pages**. Under "Branch", choose **main** and **/ (root)**, and click **Save**.
6. Wait a minute or two. Your app will be at `https://YOUR-USERNAME.github.io/five-clues/`.

## Install it on your phone

- **Android (Chrome):** open the link, then tap the menu (three dots) and choose **Install app** or **Add to Home screen**.
- **iPhone (Safari):** open the link, tap the **Share** button and choose **Add to Home Screen**.

Open it once while online so it can save itself for offline use. After that it works without internet.

## Updating the cases

Upload new `dx.js` and `rx.js` files to the repository (they replace the old ones). The app picks them up the next time it opens online. If you change `index.html` or the icons, also change `VERSION` in `sw.js` (for example to `fiveclues-v2`) so phones refresh the cached app.

Your scores are stored on each device and are kept across updates.
