# MASTERY

Personal deliberate-practice tracker. Static site; your log lives in `data/mastery.json`.

Levels (deliberate hours in one field): Beginner 0, Competent 1,000, Top of Field 2,100, National Authority 2,800, World Class 3,600. Edit the `LEVELS` list in `index.html` to change them.

## Deploy
1. Create a GitHub repo and upload these files.
2. Settings > Pages > deploy from the `main` branch, root folder.
3. Open the site and tap **Sync**. Enter your repo name and paste a fine-grained token (this repo only, Contents: read and write).
4. Every change is then committed to `data/mastery.json`, and other devices read the same file.

The token is stored only in the browser it was entered in. A public repo makes the data file public; use a private repo if you prefer.
