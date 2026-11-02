# Setup for kanna857

1. Create a public GitHub repository named `kanna857` under the `kanna857` account.
2. Upload `README.md`, the `assets/` folder, and `.github/workflows/snake.yml`, keeping their paths unchanged.
3. In repository Settings > Actions > General, allow GitHub Actions. Set Workflow permissions to **Read and write permissions** if required.
4. Open Actions > Generate contribution snake > Run workflow. Once successful, the `output` branch will contain snake SVGs.
5. Visit https://github.com/kanna857 and verify the images, external stats cards and links.

The Radha-Krishna hero is a real looping GIF with drifting petal overlays; the divider is animated SVG. GitHub README does not execute JavaScript, so animations must use GIF/SVG or externally generated images.

Project links are based on prior project names; verify that every repository exists and is public. Stats and languages are live third-party cards and may fail if those services are unavailable.

## Animation notes
The hero GIF contains looping drifting petals and pulsing golden lights. `assets/animated_heading.svg` has CSS-animated peacock feathers and glowing title. GitHub supports animated GIF and many SVG animations, but may restrict some SVG effects. GitHub statistics and graphs are loaded from external services, not invented values. If an image service is down, its card may fail to load.
