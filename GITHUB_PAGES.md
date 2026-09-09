# GitHub Pages deployment

This project is configured to build with Vite and deploy through GitHub Actions.

1. Upload/commit the project contents to the repository's `main` branch, including `.github/workflows/deploy.yml`.
2. In **Settings → Pages → Build and deployment → Source**, select **GitHub Actions**.
3. Open **Actions** and wait for **Deploy to GitHub Pages** to finish.
4. The site will be available at:
   `https://<github-username>.github.io/<repository-name>/`

Do not upload the `.env` file or commit private API keys. GitHub Pages is static hosting; server-side secrets from AI Studio do not become available just because the project is deployed there.
