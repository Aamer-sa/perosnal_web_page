# Aamer ♥ Shaista — Forever Story

## Files
- `index.html`: complete story, loading, envelopes, report, quiz, letter and proposal
- `yes.html`: Yes celebration
- `style.css`: design and responsive animation
- `script.js`: all main interaction and optional generated music
- `yes.js`: celebration confetti

## Test
Extract the ZIP, keep every file in the same folder, then open `index.html` in Chrome.

## Personalize
- Edit names/text in `index.html`.
- Edit loading lines, No-button lines, and letter in `script.js`.
- Edit celebration text in `yes.html`.
- For a photo: put `our-photo.jpg` beside `index.html`, then replace the `<div class="art">...</div>` in `index.html` with:
```html
<div class="art"><img src="our-photo.jpg" alt="Aamer and Shaista" style="width:100%;height:100%;object-fit:cover"></div>
```

## Deploy GitHub Pages
1. Create a GitHub repository.
2. Upload `index.html`, `yes.html`, `style.css`, `script.js`, `yes.js`, and this README to the repository root. Do not upload only the ZIP.
3. Go to **Settings → Pages**.
4. Choose **Deploy from a branch**, select `main` and `/(root)`, then Save.
5. Wait for GitHub to display the published URL; test it on mobile before sharing.

## Edit after deployment
Open the repository, open a file, click the edit/pencil icon, commit changes, wait 1–3 minutes, then refresh the webpage.

## Notes
Music begins after **Open my heart** is clicked, which allows it to work in modern browsers. The No-button code rejects positions that overlap or come too close to the Yes button.
