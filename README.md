# Muhammad Maaz — Portfolio

- `index.html` — the full website (photo and resume are already embedded inside it).
- `assets/` — original profile photo and resume PDF, for your records.

## Run locally
Double-click `index.html` to open it in your browser.

## Deploy on Vercel
1. Create a new GitHub repository and upload everything in this folder.
2. On vercel.com, click "Add New Project" and import that repository.
3. Leave all settings as default and click Deploy.

## Song player (YouTube)
Open `index.html` in any text editor, search for `var YT_ID = "";` near the bottom,
and paste the song's YouTube video ID between the quotes, e.g. `var YT_ID = "ABC123xyz";`
(the ID is the part after `watch?v=` in the YouTube link). Save, push to GitHub, and Vercel
will redeploy. The card then shows the video thumbnail and the play/pause button plays the song on the page.

## Featured Designs covers
Each category row in `index.html` has `style="--cover:linear-gradient(...)"`.
To use your own image, replace it with `style="--cover:url(assets/covers/motion.jpg)"`
(and put the image in `assets/covers/`). The image shows behind the row on hover.
