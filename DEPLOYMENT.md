# GitHub Pages Deployment Instructions

1. **Create a new GitHub repository** (e.g., `your-username/your-repo`).
2. **Copy all files** from the `pages` folder (including `index.html` and `.nojekyll`) to the root of your repository.
3. **Commit and push** the files to the `main` branch (or `gh-pages` branch if you prefer).
4. In your repository, go to **Settings > Pages**.
5. Under **Source**, select the branch (`main` or `gh-pages`) and the root (`/`) folder.
6. Save. Your site will be published at `https://your-username.github.io/your-repo/`.

**Tips:**
- Ensure all links in your HTML files are relative (e.g., `about.html`, not `/about.html`).
- The `.nojekyll` file disables Jekyll processing, allowing all files to be served as-is.
- For best SEO, add meta tags and a favicon to your HTML files.
