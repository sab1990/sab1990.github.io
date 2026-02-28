# Bayside Bachata Website

Static GitHub Pages site for Bayside Bachata.

## Local structure

- `index.html` contains the landing page markup.
- `styles.css` contains the site styling.
- `script.js` contains the mobile nav and reveal animations.

## Deployment

GitHub Pages deployment is configured through [`.github/workflows/deploy.yml`](/Users/sabal.shrestha/Documents/Personal/personal_repos/sab1990.github.io/.github/workflows/deploy.yml).

To publish the site from GitHub:

1. Push the repository to the `main` branch on GitHub.
2. In the GitHub repository settings, open `Settings > Pages`.
3. Set `Source` to `GitHub Actions` if it is not already selected.
4. The workflow will deploy the contents of the repository root as the Pages site.
