# Deployment Guide - GitHub Pages

This guide will walk you through deploying your academic website to GitHub Pages for free hosting.

## Step 1: Create a GitHub Repository

1. Go to [GitHub.com](https://github.com) and sign in
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Name your repository (e.g., `my-academic-website`)
5. Make it **Public** (required for free GitHub Pages)
6. Don't initialize with README (we already have one)
7. Click "Create repository"

## Step 2: Upload Your Website Files

### Option A: Using GitHub Web Interface

1. In your new repository, click "uploading an existing file"
2. Drag and drop all your website files:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `README.md`
3. Add a commit message like "Initial website upload"
4. Click "Commit changes"

### Option B: Using Git (Recommended)

1. Open terminal/command prompt
2. Navigate to your website folder
3. Run these commands:

```bash
git init
git add .
git commit -m "Initial website upload"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git
git push -u origin main
```

## Step 3: Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" tab
3. Scroll down to "Pages" section (in the left sidebar)
4. Under "Source", select "Deploy from a branch"
5. Under "Branch", select "main"
6. Click "Save"

## Step 4: Access Your Website

- Your website will be available at: `https://YOUR_USERNAME.github.io/YOUR_REPOSITORY_NAME`
- It may take a few minutes for the changes to appear
- You can check the status in the "Pages" section of your repository settings

## Step 5: Custom Domain (Optional)

If you want to use a custom domain:

1. In your repository Settings → Pages
2. Under "Custom domain", enter your domain (e.g., `yourname.com`)
3. Click "Save"
4. Add a CNAME record to your domain provider pointing to `YOUR_USERNAME.github.io`

## Troubleshooting

### Website Not Loading
- Check that your repository is public
- Verify all files are uploaded correctly
- Wait 5-10 minutes for changes to propagate

### Styling Issues
- Make sure `styles.css` is in the same directory as `index.html`
- Check that the CSS file path in `index.html` is correct

### JavaScript Not Working
- Verify `script.js` is uploaded
- Check browser console for errors
- Ensure the script tag is present in `index.html`

## Updating Your Website

### Using GitHub Web Interface
1. Go to your repository
2. Click on the file you want to edit
3. Click the pencil icon to edit
4. Make your changes
5. Commit the changes

### Using Git
```bash
git add .
git commit -m "Update website content"
git push
```

## Alternative Hosting Options

### Netlify
1. Go to [netlify.com](https://netlify.com)
2. Drag and drop your website folder
3. Get a free URL instantly

### Vercel
1. Go to [vercel.com](https://vercel.com)
2. Connect your GitHub repository
3. Automatic deployments on every push

## Performance Tips

1. **Optimize Images**: Compress images before uploading
2. **Minimize Files**: Consider minifying CSS and JS for production
3. **Use CDN**: Font Awesome and Google Fonts are already using CDNs
4. **Cache**: GitHub Pages automatically handles caching

## Security Considerations

- Keep your repository public for free hosting
- Don't include sensitive information in your website
- Use environment variables for any API keys (if you add them later)

## Need Help?

- [GitHub Pages Documentation](https://pages.github.com/)
- [GitHub Support](https://support.github.com/)
- [GitHub Community](https://github.community/)

---

**Your website should now be live!** 🚀 