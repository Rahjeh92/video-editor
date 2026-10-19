# Zain Rahjeh — Portfolio Website

Professional static portfolio built for GitHub Pages. No Node.js build or database required.

## Publish the website (GitHub Pages)

1. Extract this ZIP. **Upload the contents, not the ZIP itself.** `index.html` must be in the repository root.
2. On GitHub click **New repository**. Suggested name: `zain-portfolio` (or `YOUR-USERNAME.github.io` for a root domain). Make it **Public**.
3. Add the files, including `assets/` and `.nojekyll`. Commit to the **main** branch.
4. Navigate to **Settings → Pages → Build and deployment → Source: Deploy from a branch**. Select **main** and **/(root)** and save.
5. Your site becomes available at `https://YOUR-USERNAME.github.io/zain-portfolio/` (or `https://YOUR-USERNAME.github.io/` for a user-page repository). Publishing can take a few minutes.
6. Add the live URL to your LinkedIn and CV.

## What was fixed

- Rebranded navigation, title, About and SEO for **Zain Rahjeh** as a personal jobs portfolio.
- Showreel is a **real included video** in `assets/videos/`, not an unconfigured YouTube playlist.
- Four long-form films and five Shorts open the exact YouTube videos (including supplied timestamps). This avoids YouTube embed Error 153.
- Three AI videos, eight advertising videos and ten thumbnail works use the confirmed Google Drive file IDs, linking each item directly.
- Removed unreliable embedded Drive folder iframes. All galleries have real individual links.
- Shorts shown as compact buttons/cards without blurry preview images.
- Removed the forced intro gate, so recruiters see the portfolio immediately. 3D effects remain, where supported.
- Form opens the visitor's **own email app** and is NOT a server-backed contact form. Address currently used: `rahjeh2020@gmail.com` (change in `index.html` if needed).
- Added responsive gallery styling, favicon, better accessibility and GitHub Pages-relative local media paths.

## Important notes

- The three.js animation, GSAP motion and Google Fonts load from online CDNs, so internet access is needed for those effects. Core HTML and local showreel remain included in the repo.
- The website never needs visitors to connect Google Drive, but individual shared files must allow **Anyone with the link → Viewer** or a logged-in authorized viewer.
- Google Drive thumbnail services sometimes block image previews. If a thumbnail is unavailable, the gallery still shows the project title and working file link. For guaranteed images, replace Drive previews with local `assets/thumbs/*.webp` files.
- The grading comparison is a visual illustration, NOT a proven client before/after.
- Verify private-client case study details and client permissions before public launch.
- Check your email and personal information before publishing.
- For a professional portfolio operated from Germany, check whether you need an **Impressum** and **Datenschutzerklärung**. These legally required personal details cannot be filled in without your review.
- Do not use Git LFS for the showreel: GitHub Pages does not reliably serve LFS media in normal static page builds.

## Local test

Open `index.html` directly (local video plays, some external effects/media may have restrictions), or run a local web server:

```sh
python -m http.server 8000
```

Then open http://localhost:8000. Check the desktop/mobile layouts, Play Showreel, YouTube and Drive links, and email form.


## Image repair (this update)

- 8 original, locally generated ad stills in `assets/ads/` (extracted from the actual advertising videos).
- 10 real thumbnail designs in `assets/thumbs/` (optimized WebP).
- Thumbnails and ads galleries now display those local images; all cards still link to the original Google Drive video/image.
- The AI eCard work also has a local screenshot. The Case Files for Design and Ads use real mosaics of your work rather than synthetic placeholders.
- To update your published repository `rahjeh92/video-editor`, upload **all contents of this ZIP** to your existing repository root, with `index.html` at root. Commit, then wait for GitHub Pages deployment and hard-refresh the website (Ctrl+Shift+R).
- Do not upload just the ZIP. No need to change your existing GitHub Pages Settings.
- Video files on Drive still require visitor access. The local preview art will render independently of Drive permissions.
