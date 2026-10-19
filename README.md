# Daily Upkeep

A self-care tracker you install on your Android phone and your PC. It has daily and weekly tasks, streaks, a 14-day history and a home exercise library. It works offline, and your data stays on your device.

## 1. Put it online (free, one time, about 5 minutes)

The app needs a web address once, so your phone and PC can install it. GitHub Pages hosts it for free.

1. Create a free account at https://github.com if you don't have one.
2. Click **+** (top right) → **New repository**. Name it `daily-upkeep`, set it to **Public**, and click **Create repository**.
3. On the new repository page, click **uploading an existing file**.
4. Unzip `daily-upkeep.zip` on your PC and drag **everything inside it** into the upload area: `index.html`, `manifest.webmanifest`, `sw.js` and the `icons` folder. Click **Commit changes**.
5. Go to **Settings** → **Pages**. Under **Branch**, choose `main` and `/ (root)`, then **Save**.
6. Wait a minute and refresh. Your address appears at the top, like `https://YOUR-NAME.github.io/daily-upkeep/`.

## 2. Install on Android

1. Open your address in **Chrome**.
2. Tap the **Install app** button at the bottom of the page, or tap Chrome's **⋮** menu → **Install app** (some phones say **Add to Home screen**).
3. The Daily Upkeep icon appears on your home screen and in your app drawer. It opens full-screen like any other app.

## 3. Install on your PC

1. Open your address in **Chrome** or **Edge**.
2. Click the install icon at the right end of the address bar, or the **Install app** button on the page.
3. It opens in its own window and shows up in the Start menu. You can pin it to the taskbar.

## Moving your history between phone and PC

Each device keeps its own data. To copy your history across:

1. On the device with your history, tap **Save backup** at the bottom of the app. A `.json` file goes to your downloads.
2. Send that file to the other device (email, Google Drive, USB).
3. On the other device, tap **Load backup** and pick the file. It merges with what's already there, so nothing is lost.

Saving a backup now and then is also a good idea in case you change phones.

## Changing the app later

Edit `index.html`, then in `sw.js` change `upkeep-v1` to `upkeep-v2` (and so on each time). Upload both files to the repository again. The installed app updates itself the next time it opens with internet.

The task lists are at the top of the `<script>` section in `index.html` (`DAILY` and `WEEKLY`), if you want to change them yourself.
