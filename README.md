# Kowsi Creative Studio – Website

## Folder
index.html · styles.css · script.js · images/kowsi-logo.jpg (your official logo, unchanged)

## Edit
- Fiverr link: script.js → `FIVERR_URL = "https://www.fiverr.com/yourname"`
- Portfolio images: put files in images/portfolio/, then set `src` in the PORTFOLIO list in script.js
- Book covers: in index.html replace the `<div class="cover ph">` with `<img class="cover" src="images/books/cover.jpg" alt="Title">`
- Book descriptions, colours (:root in styles.css): edit directly.

## Publish free (pick one)
**Netlify Drop (easiest):** go to app.netlify.com/drop, drag the whole kowsi-site folder in. Live in seconds. Rename the site in Site settings.
**GitHub Pages:** create a GitHub repo, upload all files, Settings → Pages → Deploy from branch → main / root. Link: username.github.io/repo
**Cloudflare Pages:** Workers & Pages → Create → Upload assets → upload the folder.
Re-upload the folder after each edit.
