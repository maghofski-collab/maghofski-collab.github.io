# manuelagh.github.io

Personal CV site. Plain HTML, no build step.

## Files to upload (repo root)

- `index.html`
- `photo.jpg` (portrait; replace with your professional photo, same filename)
- `ultrafilters_rotary.jpg`
- `notebooks/` folder with the `.ipynb` files

## Publish on GitHub Pages

1. Create a public repo named exactly `<your-github-username>.github.io`
2. Upload the files above (Add file → Upload files; drag the `notebooks` folder in too)
3. Settings → Pages → Source: Deploy from a branch → `main` / root
4. Live at `https://<your-github-username>.github.io`

## Adding or removing a notebook

1. Upload the `.ipynb` into the repo's `notebooks/` folder.
2. In `index.html`, edit the `NOTEBOOKS` list (near the bottom): add or delete one entry.
3. The "view notebook on GitHub" link is built automatically from your username
   (repo `<username>.github.io`, branch `main`). If your repo is named differently,
   set `REPO_URL` just under the list.

Open the work tab directly with `https://<username>.github.io/#work`.
