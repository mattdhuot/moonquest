# MoonQuest STEM website

Static landing page for MoonQuest STEM. It can be hosted free with GitHub Pages.

## Preview locally

Open `index.html` in a browser. The page has no build step or software dependencies.

## Publish with GitHub Pages

1. Create a public GitHub repository.
2. Upload `index.html`, `mqs-logo.png`, and `.nojekyll` to the repository root.
3. Open the repository's **Settings > Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and `/ (root)`, then save.
6. GitHub will display the public site URL after deployment completes.

## Before launch

The inquiry form validates in the browser but intentionally does not transmit information yet. Connect it to Formspree, Web3Forms, or another form endpoint before accepting inquiries. Do not restore a success message claiming a request was received until delivery is configured and tested.

To add a custom domain later, enter it under **Settings > Pages > Custom domain**, then follow GitHub's DNS instructions for your domain provider.
