# GitHub Profile README Setup

## Snake Animation Setup Complete! ✅

The snake animation workflow has been configured and will automatically generate a snake that eats your GitHub contributions.

### What Was Created

1. **Workflow File**: `.github/workflows/snake.yml`
   - Runs automatically every 24 hours
   - Can be manually triggered from GitHub Actions tab
   - Runs on every push to main branch

### How It Works

The GitHub Action will:
1. Generate a snake animation from your contribution graph
2. Create both light and dark theme versions
3. Save them to an `output` branch in your repository
4. The README.md already references these files

### Setup Instructions

1. **Create the GitHub Repository**
   ```bash
   # Navigate to your directory
   cd C:\Users\likhi\.gemini\antigravity\scratch\likhitha-hs543
   
   # Initialize git repository
   git init
   
   # Add all files
   git add .
   
   # Commit
   git commit -m "Initial commit: Professional GitHub profile README"
   ```

2. **Create Repository on GitHub**
   - Go to https://github.com/new
   - Repository name: `likhitha-hs543` (MUST match your username exactly)
   - Make it public
   - **DO NOT** initialize with README (you already have one)
   - Click "Create repository"

3. **Push to GitHub**
   ```bash
   # Add remote
   git remote add origin https://github.com/likhitha-hs543/likhitha-hs543.git
   
   # Push to main
   git branch -M main
   git push -u origin main
   ```

4. **Enable GitHub Actions**
   - Go to your repository settings
   - Navigate to "Actions" → "General"
   - Under "Workflow permissions", select "Read and write permissions"
   - Click "Save"

5. **Trigger First Run**
   - Go to "Actions" tab in your repository
   - Click on "Generate Snake Animation" workflow
   - Click "Run workflow" → "Run workflow"
   - Wait 1-2 minutes for it to complete

6. **Verify**
   - Check that an `output` branch was created
   - Visit your profile at https://github.com/likhitha-hs543
   - The README should display with the snake animation!

### Troubleshooting

**If snake doesn't appear:**
- Make sure the repository name is exactly `likhitha-hs543`
- Ensure GitHub Actions has write permissions
- Check the Actions tab for any error messages
- The first run might take a few minutes

**If workflow fails:**
- Go to Actions tab and check the error logs
- Ensure your repository is public
- Try manually triggering the workflow again

### Next Steps

After setup, the snake will:
- Update automatically every 24 hours
- Update on every push to main
- Can be manually triggered anytime from Actions tab

---

**Note**: The repository name MUST be exactly the same as your GitHub username (`likhitha-hs543`) for the profile README to work!
