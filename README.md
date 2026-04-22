# Topic Modelling GitHub Pages Site

This folder is ready to upload to a GitHub repository and publish with **GitHub Pages**.

## Files included
- `index.html` → your published website
- `.nojekyll` → helps GitHub Pages serve the site without Jekyll processing

## Publish on GitHub Pages
1. Create a new repository on GitHub.
2. Upload all files from this folder to the repository root.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose:
   - **Source:** Deploy from a branch
   - **Branch:** `main`
   - **Folder:** `/ (root)`
5. Save.
6. GitHub will generate a live site URL.

## Recommended repository name
You can use a simple name such as:
- `topic-modelling-site`
- `pyldavis-topic-model`
- `domestic-memory-topics`

## Live URL format
If your GitHub username is `yourusername` and repo name is `topic-modelling-site`, your site will usually appear at:

`https://yourusername.github.io/topic-modelling-site/`

## Note
This site uses external CDN links for `d3.js` and `pyLDAvis`, so it needs an internet connection to load fully on GitHub Pages.
