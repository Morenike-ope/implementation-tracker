# Omaha Progress Tracker

A polished, public-facing React and Tailwind prototype for tracking comprehensive plan actions, indicators, investments, geography, community priorities, annual reporting, and data methods.

## GitHub Pages

This project is ready to host as a static GitHub Pages site. It uses local vendored browser files in `vendor/`, so the published site does not need a build step or backend.

1. Create a new GitHub repository, for example `omaha-progress-tracker`.
2. From this folder, initialize Git and push the project:

```powershell
git init
git branch -M main
git add .
git commit -m "Add Omaha Progress Tracker prototype"
git remote add origin https://github.com/YOUR-USERNAME/omaha-progress-tracker.git
git push -u origin main
```

3. In GitHub, open the repository settings and enable Pages using **GitHub Actions** as the source.
4. The included workflow at `.github/workflows/pages.yml` will publish the site after each push to `main`.

## Preview

Run the static preview server:

```powershell
& 'C:\Users\AY\.cache\codex-runtimes\codex-primary-runtime\dependencies\node\bin\node.exe' server.js
```

Then open:

```text
http://localhost:4173
```

The app uses sample data directly in `index.html` and does not require a backend.
