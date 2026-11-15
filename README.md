# Mohamed-Saiaf ALIAMINI — Academic Portfolio

A responsive academic portfolio starter built with HTML, CSS and JavaScript for GitHub Pages.

## Files
- `index.html` — page content
- `style.css` — layout and visual design
- `script.js` — mobile navigation and current year
- `assets/` — add your profile photo, CV and other files here

## Before publishing
Search in `index.html` and replace:
- `YOUR.EMAIL@EXAMPLE.COM` with your professional email.
- `https://www.linkedin.com/` with your LinkedIn profile URL.
- `https://github.com/` with your GitHub profile URL.
- The IRD/CIRAD experience placeholders with your exact job titles and dates.
- Add verified publication details and links only when available.

Your ORCID is currently set in the hero link as `0009-0000-7980-1414`. Check the ORCID URL before publishing.

## Add your photo
1. Put your portrait in `assets/profile.jpg`.
2. In `index.html`, replace:
   `<div class="portrait-placeholder"><span>MSA</span><small>ADD YOUR PHOTO</small></div>`
   with:
   `<img class="profile-photo" src="assets/profile.jpg" alt="Portrait of Mohamed-Saiaf Aliamini">`
3. Add this CSS rule to `style.css`:
   `.profile-photo{width:100%;height:100%;object-fit:cover;border-radius:48% 48% 5px 5px}`

## Publish on GitHub Pages
1. Create a GitHub repository named exactly `YOUR-GITHUB-USERNAME.github.io`.
2. Upload all files and folders from this project to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then Save.
6. Your website will be published at `https://YOUR-GITHUB-USERNAME.github.io/`.

If you instead use a repository named `Portfolio`, the URL will be:
`https://YOUR-GITHUB-USERNAME.github.io/Portfolio/`
