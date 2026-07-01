# The Oracle's Die 🎲

Cast a die and let chance name one of 86 ancient Greek writers — with their era and a
representative work. Built as a small, dependency-free static site.

## Files
- `index.html` — the dice-roll page
- `result.html` — the single-author result page
- `authors.js` — the 86-author dataset (name, fields, era, representative work)
- `style.css` — shared styling

## Run locally
Just open `index.html` in any browser. No build step, no server needed.

## Publish on GitHub Pages (so others can play)

1. **Create a repository** on GitHub, e.g. `greek-oracle-die`. Make it **Public**.
2. **Upload these four files** to the repository root:
   - Click **Add file → Upload files**, drag in `index.html`, `result.html`,
     `authors.js`, `style.css`, then **Commit changes**.
   - (Or, via git: `git init`, `git add .`, `git commit -m "Oracle's Die"`,
     `git branch -M main`, `git remote add origin <your-repo-url>`, `git push -u origin main`.)
3. **Turn on Pages**: repo **Settings → Pages** → under *Build and deployment*,
   set **Source = Deploy from a branch**, **Branch = main**, **Folder = / (root)**, **Save**.
4. Wait ~1 minute. Your live URL appears at the top of that Pages settings screen:
   `https://<your-username>.github.io/greek-oracle-die/`
5. Share that link — anyone can open it and play, no login required.

### Notes
- `index.html` must sit at the repository root (not in a subfolder) for the root URL to work.
- Everything runs client-side, so the site is free to host and needs no backend.
