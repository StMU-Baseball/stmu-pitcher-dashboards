# STMU Individual Pitcher Dashboards

## Hosting Setup Instructions

### Option 1: GitHub Pages (Recommended - Free)

1. **Create a GitHub account** (if you don't have one):
   - Go to https://github.com/signup

2. **Create a new repository**:
   - Click the "+" icon → "New repository"
   - Name it: `stmu-pitcher-dashboards`
   - Make it **Private** (so only people with links can access)
   - Check "Add a README file"
   - Click "Create repository"

3. **Upload the dashboard files**:
   - Click "Add file" → "Upload files"
   - Drag all the `.html` files from this folder
   - Click "Commit changes"

4. **Enable GitHub Pages**:
   - Go to Settings → Pages
   - Under "Source", select "main" branch
   - Click "Save"
   - Wait a few minutes for deployment

5. **Share links with pitchers**:
   - Your dashboards will be at: `https://[your-username].github.io/stmu-pitcher-dashboards/`
   - Individual pitcher URLs:
     - `https://[your-username].github.io/stmu-pitcher-dashboards/Christian_Molinar_dashboard.html`
     - `https://[your-username].github.io/stmu-pitcher-dashboards/Brandon_Vasquez_dashboard.html`
     - etc.

### Option 2: Netlify Drop (Even Easier - Free)

1. **Go to Netlify Drop**:
   - Visit https://app.netlify.com/drop

2. **Drag and drop**:
   - Simply drag the entire `individual_dashboards` folder onto the page
   - It will instantly deploy

3. **Get your links**:
   - Netlify gives you a URL like: `https://random-name-123.netlify.app/`
   - Share individual files: `https://random-name-123.netlify.app/Christian_Molinar_dashboard.html`

### Option 3: Simple Python HTTP Server (For Testing)

If you just want to test or share locally on your network:

```powershell
cd "C:\Trackman CSV Files\stmu_project\outputs_stmu\individual_dashboards"
python -m http.server 8080
```

Then share: `http://your-computer-ip:8080/Christian_Molinar_dashboard.html`

---

## Files in this folder:
- Christian_Molinar_dashboard.html
- Derek__Maples_dashboard.html
- Brandon_Vasquez_dashboard.html
- Edward_Mendoza_dashboard.html
- Eric_Tenery_dashboard.html
- Gabe_Cook_dashboard.html
- Joel_Burgess_dashboard.html
- Kaleb_Gauna_dashboard.html
- Matthew_Janecek_dashboard.html
- Ryan_Perez_dashboard.html
- Trae_Allen_dashboard.html

Each file contains:
- ✅ Embedded pitcher data
- ✅ Embedded StMU logo
- ✅ All interactive charts and visualizations
- ✅ Works on any device with internet connection
