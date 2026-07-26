# VMK — Portfolio

A multi-page personal portfolio site (plain HTML/CSS, no build step).

## Structure

```
├── index.html          # Home
├── work.html            # Project case studies
├── reliability.html     # Production issues log
├── skills.html          # Tech stack
├── about.html           # About + photo
├── contact.html         # Contact info
├── assets/
│   ├── css/style.css    # Shared stylesheet
│   └── img/profile.jpg  # Profile photo
└── README.md
```

## Before publishing

Open `contact.html` and swap in your real details:
- Email address
- LinkedIn URL

## Hosting on GitHub Pages

1. Create a new repository on GitHub (e.g. `yourusername.github.io` for a root domain, or any name like `portfolio` for a project site).
2. Push these files to the repository root:
   ```bash
   git init
   git add .
   git commit -m "Initial portfolio"
   git branch -M main
   git remote add origin https://github.com/<your-username>/<repo-name>.git
   git push -u origin main
   ```
3. On GitHub, go to **Settings → Pages**.
4. Under **Build and deployment → Source**, choose **Deploy from a branch**.
5. Set **Branch** to `main` and folder to `/ (root)`, then click **Save**.
6. Wait 1–2 minutes. Your site will be live at:
   - `https://<your-username>.github.io/` (if the repo is named `<your-username>.github.io`), or
   - `https://<your-username>.github.io/<repo-name>/` (for any other repo name).

No build tools, frameworks, or `npm install` needed — GitHub Pages serves these files as-is.
