# QR Landing Page (GitHub Pages)

This is a minimal, mobile‑friendly landing page that shows two buttons (English and Portuguese) 
and opens a PDF for each language. Perfect for a single QR code that serves two audiences.

## Quick start

1. Create a repository on GitHub (public is easiest), e.g. `portfolio-qr`.
2. Put these files in the repository root.
3. Ensure the `pdf/` folder contains your actual PDF files:
   - `pdf/portfolio-en.pdf`
   - `pdf/portfolio-pt.pdf`
4. Push to the `main` branch.

## Enable GitHub Pages

- Go to **Settings → Pages → Build and deployment**.
- **Source:** “Deploy from a branch”
- **Branch:** `main` and **/ (root)** (or `/docs` if you move files into `/docs`).
- Save. After a minute, your site will be live at something like:
  `https://<your-username>.github.io/<repo-name>/`

## Make the QR code

Use any QR generator and paste the site URL above. Print it.

## Customize

- Edit `index.html` styles, title, and footer (© Your Name).
- If you prefer `/docs` as your Pages source, move all project files into a `docs/` folder and update links if needed.
