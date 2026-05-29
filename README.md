# Omaha Progress Tracker

A prototype/proposal for tracking comprehensive plan actions, indicators, investments, geography, community priorities, annual reporting, and data methods.

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

3. In GitHub, open the repository settings and go to **Pages**.
4. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
5. Set **Branch** to `main` and the folder to `/root`, then save.

GitHub will publish the site from `index.html` in the repository root.

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
