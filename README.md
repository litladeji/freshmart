
  # Website Design

  This is a code bundle for Website Design. The original project is available at https://www.figma.com/design/1DGOIfo0wc6dLgFTuFH9tj/Website-Design.

  ## Running the code

  Run `npm i` to install the dependencies.

  Run `npm run dev` to start the development server.

## Deployment

GitHub Pages deployment is automated through `.github/workflows/deploy.yml`.

1. Push changes to the `main` branch (or trigger the workflow manually) and GitHub Actions will install dependencies, run the production build, and publish the `build` directory to Pages.
2. After the first run, confirm the repository’s **Settings → Pages** is set to the `GitHub Actions` source. The workflow outputs the final URL (for this repo it will be `https://litladeji.github.io/freshmart/`).

> Need to preview the same build locally? Run `GITHUB_PAGES=true npm run build` to generate the `build` folder with the GitHub Pages base path applied.
  