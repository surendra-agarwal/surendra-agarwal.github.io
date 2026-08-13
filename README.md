# Surendra Agarwal — Personal Website

A single-page portfolio site (dark executive theme) built from your resume and LinkedIn profile.

## Files
- `index.html` — the entire site (HTML/CSS/JS in one file)
- `assets/Surendra_Agarwal_Resume.pdf` — resume, linked from the "Download Resume" buttons
- `assets/Surendra_Agarwal_Resume.docx` — editable resume source
- `assets/images/` — drop your headshot photo here (see below)

## Adding your photo
Open `index.html`, find the comment near `<div class="portrait" id="portrait">`
(inside the Hero section), and replace the `SA` initials `<span>` with:

    <img src="assets/images/headshot.jpg" alt="Surendra Agarwal">

Then place your photo file at `assets/images/headshot.jpg` (a square, well-lit
headshot works best — it will be cropped into a circle).

## Deploying to GitHub Pages
1. Create a new GitHub repository (e.g. `surendra-agarwal.github.io` for a root
   domain, or any name like `portfolio` for a project page).
2. Upload all files in this folder (keeping the `assets/` folder structure) to
   the repository's main branch.
3. In the repo, go to Settings → Pages → set Source to "Deploy from a branch",
   branch `main`, folder `/ (root)`. Save.
4. GitHub will publish the site at `https://<your-username>.github.io/<repo-name>/`
   (or `https://<your-username>.github.io/` if you used the special repo name
   above). It usually goes live within a minute or two.
