# Deployment Instructions

To deploy changes to your GitHub Pages site:

## 1. Commit your changes
```bash
git add index.html
git commit -m "Update website with profile picture and design enhancements"
```

## 2. Push to remote
```bash
git push origin main
```

## Alternative: Use SSH (if configured)
If you have SSH keys set up:
```bash
git remote set-url origin git@github.com:keonipkim/keonipkim.github.io.git
git push origin main
```

## Note:
If you encounter authentication issues with HTTPS, you may need to:
1. Use a personal access token instead of password
2. Configure credential caching: `git config --global credential.helper cache`
3. Or switch to SSH authentication