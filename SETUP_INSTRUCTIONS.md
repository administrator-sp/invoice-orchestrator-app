# 🚀 Setup Instructions for Intuit Production Requirements

## Files in This Folder

- `index.html` - Main app landing page
- `disconnect.html` - Disconnect page for users
- `EULA.md` - End User License Agreement
- `PRIVACY_POLICY.md` - Privacy Policy
- `README.md` - Repository description

## Step-by-Step Setup

### 1. Upload to Your Company GitHub Repository

**Option A: Create New Repository (Recommended)**
1. Go to your company's GitHub organization
2. Click "New Repository"
3. Name: `invoice-orchestrator-app` (or similar)
4. Visibility: **Public** (required for GitHub Pages)
5. Click "Create repository"

**Option B: Use Existing Repository**
1. Navigate to an existing company repository
2. Create a new folder: `/invoice-app/`
3. Upload files there

### 2. Upload These Files

Upload all files from this folder to your GitHub repository:
- `index.html`
- `disconnect.html`
- `EULA.md`
- `PRIVACY_POLICY.md`
- `README.md`

### 3. Enable GitHub Pages

1. Go to repository **Settings**
2. Scroll to **Pages** section (left sidebar)
3. Under "Build and deployment":
   - Source: **Deploy from a branch**
   - Branch: **main** (or master)
   - Folder: **/ (root)**
4. Click **Save**
5. Wait 1-2 minutes for deployment

### 4. Get Your URLs

After GitHub Pages is enabled, your URL will be:
```
https://YOUR-COMPANY-NAME.github.io/REPO-NAME/
```

For example:
- If your GitHub org is "subpop"
- And repo name is "invoice-orchestrator-app"
- Your URL is: `https://subpop.github.io/invoice-orchestrator-app/`

### 5. Fill in Intuit Developer Dashboard

Once GitHub Pages is live, use these URLs in Intuit:

**Host Domain:**
```
YOUR-COMPANY-NAME.github.io
```

**Launch URL:**
```
https://YOUR-COMPANY-NAME.github.io/REPO-NAME/
```

**Disconnect URL:**
```
https://YOUR-COMPANY-NAME.github.io/REPO-NAME/disconnect.html
```

**EULA URL:**
```
https://YOUR-COMPANY-NAME.github.io/REPO-NAME/EULA.md
```

**Privacy Policy URL:**
```
https://YOUR-COMPANY-NAME.github.io/REPO-NAME/PRIVACY_POLICY.md
```

### 6. Other Intuit Requirements

**Category:** Select "Accounting"

**Regulated Industries:** Select "None"

**Hosting Location:** Select "Cloud"

## Verification

After setup, verify your URLs work:
1. Visit your GitHub Pages URL in a browser
2. Check that all pages load correctly
3. Verify HTTPS is working
4. Then enter URLs in Intuit Developer Dashboard

## Need Help?

If you have trouble with GitHub:
1. Make sure repository is **Public**
2. Make sure GitHub Pages is enabled
3. Wait a few minutes after enabling Pages
4. Check GitHub Actions tab for deployment status

---

**You're ready to complete the Intuit production requirements!**
