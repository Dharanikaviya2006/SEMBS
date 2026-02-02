# GitHub Pages Deployment Guide

This guide will help you deploy the Event Photo Branding Tool to GitHub Pages.

## Step-by-Step Instructions

### 1. Create a GitHub Repository

1. Go to [GitHub](https://github.com) and sign in
2. Click the "+" icon in the top right corner
3. Select "New repository"
4. Enter a repository name (e.g., `event-photo-branding`)
5. Choose "Public" (required for free GitHub Pages)
6. Click "Create repository"

### 2. Upload Your Files

**Option A: Using GitHub Web Interface**

1. On your repository page, click "Add file" → "Upload files"
2. Drag and drop these files:
   - `index.html`
   - `he5logo.svg` (or `he5logo.png`)
3. Click "Commit changes"

**Option B: Using Git Command Line**

```bash
# Initialize git in your project folder
git init

# Add all files
git add .

# Commit files
git commit -m "Initial commit"

# Connect to your GitHub repository
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPO-NAME.git

# Push to GitHub
git branch -M main
git push -u origin main
```

### 3. Enable GitHub Pages

1. Go to your repository on GitHub
2. Click "Settings" (top menu)
3. Click "Pages" (left sidebar)
4. Under "Source":
   - Select branch: `main`
   - Select folder: `/ (root)`
5. Click "Save"

### 4. Access Your Live Site

After a few minutes, your site will be live at:
```
https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/
```

For example: `https://johndoe.github.io/event-photo-branding/`

## Custom Domain (Optional)

If you want to use a custom domain:

1. Go to Settings → Pages
2. Under "Custom domain", enter your domain
3. Click "Save"
4. Update your domain's DNS settings:
   - Add a CNAME record pointing to `YOUR-USERNAME.github.io`

## Updating Your Site

Whenever you make changes:

**Web Interface:**
1. Go to your repository
2. Click on the file you want to edit
3. Click the pencil icon to edit
4. Make changes and commit

**Git Command Line:**
```bash
git add .
git commit -m "Update description"
git push
```

Your site will automatically update within a few minutes!

## Troubleshooting

### Site Not Loading
- Wait 5-10 minutes after first deployment
- Check that GitHub Pages is enabled in Settings
- Ensure your repository is public

### Logo Not Showing
- Verify `he5logo.png` or `he5logo.svg` is in the root directory
- Check the file name matches exactly (case-sensitive)
- The app will use a fallback logo if the file isn't found

### Images Not Downloading
- Make sure you're using HTTPS (not HTTP)
- Try a different browser
- Check browser console for errors (F12)

## Best Practices

1. **Test Locally First**: Open `index.html` in your browser before deploying
2. **Keep Files Small**: Optimize your logo file size
3. **Use HTTPS**: Always access via `https://` for full functionality
4. **Mobile Testing**: Test on mobile devices for touch interactions

## Resources

- [GitHub Pages Documentation](https://docs.github.com/en/pages)
- [Git Basics Tutorial](https://git-scm.com/book/en/v2/Getting-Started-Git-Basics)
- [Markdown Guide](https://www.markdownguide.org/) (for editing README files)

---

**Need Help?** Check the README.md file for app usage instructions or open an issue on GitHub.
