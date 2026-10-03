# Aamer ♥ Shaista — Complete Romantic Proposal Website

## Included features
- Welcome screen and five-step romantic loading screen
- Soft falling hearts and sparkle background
- Built-in optional “our song” sound button
- Timeline, envelope-opening reasons, compatibility report, and quiz
- Wrong quiz answer = ❌ effect; correct answer = 🥰 effect
- Typewriter love letter
- No button stays inside the proposal button section, runs farther away, displays messages, and makes Yes pulse stronger
- Separate Yes celebration page with confetti and Aamer’s name

## Test it first
1. Extract the ZIP.
2. Keep every file in the same folder.
3. Open `index.html` in Chrome or another browser.
4. Tap **Open my heart** and test every section.

## Change content
Edit using VS Code, Notepad++, or a phone code editor.
- `index.html`: names, timeline, envelope messages, question, and proposal text.
- `script.js`: loading lines (`loadMessages`), No-button messages (`words`), and the personal letter (`const text`).
- `yes.html`: celebration message and signature.

## Add your own photo
1. Put an image such as `our-photo.jpg` beside `index.html`.
2. In `index.html`, replace the complete `<div class="moon-art"> ... </div>` section with:
```html
<div class="moon-art"><img src="our-photo.jpg" alt="Aamer and Shaista" style="width:100%;height:100%;object-fit:cover"></div>
```
3. Upload the photo with the other files. Image filename spelling must match exactly.

## Use a real background song
This project includes a small browser-generated melody; it starts only when the visitor presses the music button. To use your own royalty-free or personally owned MP3 later, add `our-song.mp3` to the folder and ask a developer to replace the Web Audio section in `script.js` with an HTML audio player. Do not upload copyrighted music unless you have permission.

## Deploy to GitHub Pages
1. Create a new GitHub repository, for example `aamer-shaista-story`.
2. Upload the files inside this extracted folder: `index.html`, `yes.html`, `style.css`, `script.js`, `yes.js`, and `README.md`. Do not upload the ZIP as the website itself.
3. Ensure `index.html` is in the repository root, not inside an extra subfolder.
4. Open repository **Settings** → **Pages**.
5. Under Build and deployment, choose **Deploy from a branch**.
6. Select branch `main` and folder `/(root)`, then press Save.
7. Wait a few minutes. GitHub shows the exact public URL in Settings → Pages.
8. Test the URL on your phone before sending it.

## Change after deployment
1. Open your GitHub repository.
2. Open a file and click the pencil/Edit icon.
3. Save using **Commit changes**.
4. Wait 1–3 minutes and refresh the webpage.

## Troubleshooting
- **404/blank site:** `index.html` must be at the selected publishing root.
- **Changes not visible:** wait a few minutes, hard refresh, or open incognito.
- **Image absent:** confirm the image name and capitalization match exactly.
- **No music:** press the music button; browsers block audio until a person interacts with the page.

## Privacy
Use only photos, music, and messages that both of you are comfortable sharing. Keep the final URL private until the proposal moment.
