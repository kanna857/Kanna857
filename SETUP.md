# Publish both experiences

1. Create or open the public GitHub repository `kanna857/kanna857`.
2. Upload `README.md`, `assets/`, `.github/`, `docs/`, and `music/` preserving paths.
3. Go to **Settings → Pages → Build and deployment**. Choose **Deploy from a branch**, branch **main**, folder **/docs**, and Save.
4. Wait for the Pages deployment. The music button in README links to `https://kanna857.github.io/kanna857/`.
5. Open the website and press **Play Divine Flute**. Browsers block autoplay, so sound starts on user interaction.
6. In **Actions**, run the snake workflow if desired. Ensure the workflow can write to its output branch.

The melody in `docs/original-vrindavan-flute.wav` was composed/synthesized specifically for this package; it is not an existing recording. The website fetches public repository/follower counts from the GitHub API, which may temporarily rate-limit anonymous requests. Project links should be checked before publishing. GitHub README cannot play inline audio, so its glowing flute SVG links to the website.
