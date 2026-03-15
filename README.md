# Fernando Rufo Portfolio

Static portfolio website based on the CV PDF and speaker image in this folder.

## Local preview

Open `index.html` directly, or run a simple local server:

```powershell
python -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy with GitHub Pages

1. Create a new GitHub repository.
2. Upload these files to the repository root.
3. Make sure the default branch is named `main`.
4. In GitHub, go to `Settings > Pages`.
5. Under `Build and deployment`, set `Source` to `GitHub Actions`.
6. Push to `main`.
7. GitHub will publish the site automatically using `.github/workflows/deploy.yml`.

The site will be available at:

`https://<your-github-username>.github.io/<repo-name>/`

## Files

- `index.html`: page structure and content
- `styles.css`: layout, visual design, responsive behavior
- `assets/`: CV PDF and profile image used by the website
