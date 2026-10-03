# Tilawah website (needed for both store apps)

The store apps open this website inside a native app shell, so it has to be online first.
You'll need a computer. It takes about 15 minutes.

## 1. Fill in the privacy policy
Open privacy.html in a text editor (Notepad or TextEdit). Near the bottom, replace
[YOUR NAME] and [YOUR EMAIL ADDRESS] with the name and email you want shown publicly. Save.

## 2. Put it on GitHub Pages
1. Sign up or sign in at github.com. Note your username.
2. Click **+** (top right), then **New repository**.
   - Repository name: `YOUR-USERNAME.github.io` (your real username, all lowercase).
     Any name works for installing on phones, but the Google Play version needs this exact name.
   - Choose **Public**. Click **Create repository**.
3. Click **uploading an existing file**. Drag in everything from this folder, including the
   **fonts** folder. Click **Commit changes**.
4. Click **Add file**, then **Create new file**. Name it `.nojekyll` (with the dot), leave it empty,
   and click **Commit changes**. This lets GitHub serve the app-verification file in step 3 of the store guide.
5. Go to **Settings**, then **Pages**. Set Source to **Deploy from a branch**, Branch **main**,
   folder **/ (root)**, then **Save**.
6. After a couple of minutes, open `https://YOUR-USERNAME.github.io/` on your phone to check it works.
   The privacy policy is at `https://YOUR-USERNAME.github.io/privacy.html`.

## 3. Install it on phones (no store needed)
Anyone can install the app straight from the website, on iPhone or Android:
- When the site opens in Safari or Chrome, an **Install Tilawah** banner appears. Tap **Install**.
  - On Android, Chrome asks to confirm; tap **Install**.
  - On iPhone, the app shows the steps: tap Share, then **Add to Home Screen**, then **Add**.
- If the banner was closed, go to **More**, then **Add Tilawah to your home screen**.

## Updating the app later
Upload a new index.html to the repository. Both store apps pick up the change within minutes,
without a new store submission.
