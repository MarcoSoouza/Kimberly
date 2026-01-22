# Deploy Kimberly Marketing Website

## Steps to Complete Deployment

1. **Authenticate GitHub CLI**:
   - Run `gh auth login` in the terminal and follow the prompts to authenticate with your GitHub account.

2. **Create GitHub Repository**:
   - Run: `gh repo create kimberly-marketing-site --public --source=. --remote=origin --push`

3. **Enable GitHub Pages**:
   - Go to the repository on GitHub (https://github.com/YOUR_USERNAME/kimberly-marketing-site)
   - Navigate to Settings > Pages
   - Under "Source", select "Deploy from a branch"
   - Choose "main" branch and "/ (root)" folder
   - Click "Save"

4. **Access Your Site**:
   - After a few minutes, your site will be available at: `https://YOUR_USERNAME.github.io/kimberly-marketing-site/`
   - Note: The main page is `Home.html`, so you may want to rename it to `index.html` for the root URL.

## Alternative Manual Method

If you prefer not to use GitHub CLI:

1. Go to GitHub.com and create a new repository named "kimberly-marketing-site"
2. Push your code to the repository:
   ```
   git remote add origin https://github.com/YOUR_USERNAME/kimberly-marketing-site.git
   git push -u origin main
   ```
3. Enable GitHub Pages as described above.

## Notes

- The website is a static site with HTML, CSS, and images
- All files are ready for deployment
- The site includes Home, Services, and Contact pages
