# Maria Alcalde | GitHub Pages portfolio

## Preview locally
Extract the ZIP, then open `index.html` in Chrome or Edge. For reliable embedded previews, use a local server: from this folder run `python -m http.server 8000` and visit http://localhost:8000. No installation or build step is required for hosting.

## Publish to GitHub Pages
1. Sign in at https://github.com and find your exact username.
2. Create a new **public** repository named `YOUR-USERNAME.github.io`, substituting your actual username. If that repository already exists, use it instead of making another.
3. Extract the ZIP. In the repository choose **Add file > Upload files** (or the initial uploading link). Upload `index.html`, `style.css`, `script.js`, `README.md`, and the entire `assets` folder at the repository root. Do not upload the ZIP itself or nest all files inside an extra directory. Commit changes.
4. Open the repository **Settings > Pages**. Under Build and deployment choose **Deploy from a branch**, select `main` and `/ (root)`, then Save. Wait for GitHub to show a published URL; it should be `https://YOUR-USERNAME.github.io/` for a user site. If the branch is named differently, select that branch.
5. Visit the published URL and test the mobile menu, light/dark mode, project previews, resume download and direct email. Copy the live URL into OnlineJobs.ph's portfolio field.

## Personalize before sharing publicly
- Photo: the supplied professional portrait is included as `assets/profile.jpg`, with `PHOTO_ENABLED=true` in `script.js`. To change it, replace that JPEG. The monogram remains the fallback if the photo fails to load.
- Existing portfolio samples: place sanitized original files and preview PDFs or images in `assets/projects/`. Edit the `projects` array in `script.js`: fill in `preview` and `file`, using relative paths such as `assets/projects/dashboard.pdf` and `assets/projects/dashboard.xlsx`. Update the relevant description to remove “Existing sample to be added.” For forms, use a screenshot or anonymized PDF rather than private response links. Do not share personal student information or internal records.
- Demonstrations: these are AI-assisted starter materials based on a fictional coffee shop. Review, recreate, personalize and test them yourself; describe your actual contribution accurately. The social sample is HTML, not a native Canva project. The customer sample is CSV; import into Excel/Sheets and add filtering and validation as instructed on its preview page.
- Resume: the PDF uses provided information only; confirm duties, dates, and availability and replace the PDF in `assets` if revised.
- Email: the form intentionally uses a `mailto:` draft, not a server or a submission database. A configured email app is needed; the visitor must send the draft themselves. A hosted form service may be connected separately if desired.
- Public data: your supplied name, email, city/province, credentials, and availability will be publicly visible. Verify applicable DepEd/Civil Service requirements before taking additional employment.
- The GitHub username was not supplied. No website has been published from this package.
