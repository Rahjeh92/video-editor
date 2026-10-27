# Zain Rahjeh: Video Editor & Creative Portfolio

**A cinematic, interactive portfolio showcasing my work in video editing, storytelling, AI filmmaking, motion graphics, and visual design.**

🌐 **Live website:** [rahjeh92.github.io/video-editor](https://rahjeh92.github.io/video-editor/)

## About the project

I created this website to bring my creative work together in one place. Rather than using a traditional portfolio template, I wanted the experience itself to reflect the way I approach editing: visual storytelling, attention to detail, smooth pacing, and sound that supports the picture.

The result is a responsive, cinematic portfolio with animated transitions, interactive project galleries, 3D visuals, and optional sound effects. It is designed to make it easy for recruiters, studios, and clients to explore my work and get in touch.

## What's inside

- **Storytelling & long-form editing**: selected YouTube videos and narrative-driven edits.
- **Short-form content**: Reels and Shorts made for social platforms.
- **AI films & VFX**: creative experiments and finished AI-assisted film projects, including *Shadow Run / Cyberpunk Film* and *Samurai*.
- **Ads & commercial work**: promotional videos and social media advertisements.
- **Color grading & motion**: visual treatment, graphics, and post-production techniques.
- **Thumbnails & design**: a selection of my graphic and YouTube thumbnail designs.
- **Creative showreel**: an overview of my editing style and creative range.

## Website features

- Responsive layout for desktop, tablet, and mobile
- Interactive galleries and project case studies
- Three.js visual effects and GSAP scroll-based animations
- Custom sound effects with an **SFX ON / OFF** toggle
- Accessible motion preferences for visitors who request reduced animation
- Lightweight, optimized **WebP** project previews
- Direct links to full videos on YouTube and Google Drive
- Contact section with email and LinkedIn links

## Built with

| Technology | Purpose |
| --- | --- |
| HTML5 | Website structure and content |
| CSS3 | Visual identity, layouts, and responsive design |
| Vanilla JavaScript | Navigation, galleries, interactions, and case studies |
| Three.js | 3D graphics and visual effects |
| GSAP + ScrollTrigger | Motion design and scroll animations |
| Web Audio API | Interactive sound effects |
| GitHub Pages | Static website hosting |

## Run locally

No build step or framework installation is needed.

1. Clone the repository:

   ```bash
   git clone https://github.com/rahjeh92/video-editor.git
   ```

2. Open the `video-editor` folder.
3. Open `index.html` in a browser, or serve the folder with a local server for a more reliable preview:

   ```bash
   python -m http.server 8000
   ```

4. Visit [http://localhost:8000](http://localhost:8000).

> Some animation libraries and fonts load from external CDNs, so an internet connection is recommended. Browser audio policies may require your first click or tap before sound effects can play.

## Project videos and assets

The repository includes optimized preview images and website files. To keep the site fast and GitHub Pages-friendly, full-length videos are hosted externally and linked to their original YouTube or Google Drive pages. This also avoids uploading large video files to the repository.

Project links can be updated in `index.html`, and preview images are organized in the `assets/` folder.

## Deployment

This portfolio is hosted on **GitHub Pages** from the `main` branch.

To publish an update, commit the changed website files to the repository. GitHub Pages serves `index.html` from the repository root. No server or backend deployment is required.

## Let's connect

I'm based in Germany and open to video editing opportunities, creative collaborations, and remote projects.

- **Portfolio:** [rahjeh92.github.io/video-editor](https://rahjeh92.github.io/video-editor/)
- **LinkedIn:** [linkedin.com/in/zain-rahjeh92](https://www.linkedin.com/in/zain-rahjeh92/)
- **Email:** [rahjeh2020@gmail.com](mailto:rahjeh2020@gmail.com)

---

**© 2026 Zain Rahjeh.** All portfolio video, imagery, and project materials are presented for demonstration purposes. Third-party libraries and media remain subject to their respective licenses and ownership.

## Latest adjustments

- I describe my editing experience as **4+ years** throughout the portfolio.
- The production process begins with **Brief & Media Prep** and closes with **QC & Export**.

## Interactive color-grading comparison

I included a before/after slider in the Color Grading section using a frame from my `Color Grading #2` video. The **Graded** side is the actual final shot; the **Flat / LOG-style** side is a reconstructed preview from the same frame rather than an untouched camera LOG original. This lets visitors compare the visual treatment without the subject moving between shots. Both WebP images are saved locally under `assets/images/` to work reliably on GitHub Pages.


### Color Grading Comparison

Drag anywhere across the comparison image using a mouse or finger to reveal the simulated flat LOG-style preview versus the actual graded image. For keyboard operation, Tab to the comparison and use the arrow keys. The flat image is a reconstruction, not the original camera LOG file.


### RGB waveform / parade (v15)

The Color Grading section includes a three-channel RGB parade below the LOG-style / GRADED comparison. It uses locally generated WebP parade images sourced from the same grading footage to display reliably on GitHub Pages, file:// local previews, iPhones and desktops without requiring cross-origin canvas pixel reads. Sliding the main control adjusts the visual split in the RGB parade as well. This is a color scope, not an audio waveform.
