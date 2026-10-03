# Our Little Story — Proposal Website

This is a complete, mobile-friendly static proposal website. It contains a cute introduction, memories timeline, reasons-you-love-her cards, a funny compatibility score, mini quiz, typed love letter, proposal screen, moving **No** button, and a confetti celebration page.

## 1. Test it first
1. Extract this ZIP file.
2. Open the extracted folder.
3. Double-click `index.html` (or open it in Chrome).
4. Test the journey and click **Yes, forever!**.

## 2. Personalize it before deploying
Use any text editor (VS Code, Notepad++, or even a phone code editor). Search and replace these words:

- `YOUR NAME` — your name, in `index.html` and `yes.html`.
- `My Love` — her name or special nickname, in `index.html`.
- The four timeline memories in `index.html`.
- The six reason cards in `index.html`.
- The letter text inside `script.js`, starting with `const letter=`.

### Add your photos (optional)
1. Put an image like `our-photo.jpg` in the same folder as `index.html`.
2. In `index.html`, replace the whole line beginning `<div class="hero-art">` and ending `</div>` with:

```html
<div class="hero-art"><img src="our-photo.jpg" alt="A memory of us" style="width:100%;height:100%;object-fit:cover"></div>
```

Use only photos you both are comfortable sharing. Keep photos reasonably small (under about 2 MB) for faster mobile loading.

## 3. Deploy with GitHub Pages
1. Sign in at GitHub and choose **New repository**.
2. Name it something private-looking, such as `little-moon-story`.
3. Upload the **files inside this extracted folder**: `index.html`, `yes.html`, `style.css`, `script.js`, `yes.js`, and this README. Do not upload the ZIP itself.
4. Ensure `index.html` is at the repository root, not inside another folder.
5. Open the repository’s **Settings** tab → **Pages**.
6. Under **Build and deployment**, choose **Deploy from a branch**.
7. Select branch **main** and folder **/(root)**, then press **Save**.
8. Wait a few minutes. The Pages screen will show your published URL in this format:
   `https://YOUR-GITHUB-USERNAME.github.io/YOUR-REPOSITORY-NAME/`
9. Open the URL on your phone before sharing it.

## 4. Make changes after deployment
1. Open the GitHub repository.
2. Click the file you want to edit, such as `index.html`.
3. Click the pencil/edit icon.
4. Make the change and choose **Commit changes**.
5. Wait a short time, then refresh your website. GitHub Pages republishes the updated version automatically.

For bigger edits: change files on your laptop, then upload the replacement files to the same repository.

## 5. Troubleshooting
- **Site does not open:** Confirm GitHub Pages is enabled and you are using the exact URL displayed in Settings → Pages.
- **404 / blank page:** Ensure `index.html` is in the selected root folder.
- **Photo missing:** Check image spelling and uppercase/lowercase exactly match. Upload the image to the same folder.
- **Changes not visible:** Wait 1–3 minutes and hard-refresh the browser.

## Important
The No button is intentionally playful. The real point is the personal message and the Yes path. Keep the final proposal kind, respectful, and personal.
