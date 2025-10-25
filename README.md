# US Plastics Recycling Infrastructure Map

Interactive map showing MRFs, Mills/Reclaimers, and Brokers with coverage areas across the United States.

## 🗺️ Features

- **440 MRFs** (Material Recovery Facilities) - Blue markers sized by capacity
- **217 Mills/Reclaimers** - 6 separate layers with color-coded facility types:
  - Chemical/Advanced Recycling (Red)
  - Compounder (Forest Green)
  - Converter (Lime Green)
  - End-User (Light Green)
  - Reclaimer (Green)
  - Secondary Processor (Orange)
- **8 Brokers** - Purple translucent 250-mile radius coverage areas

## 🚀 Deploy to GitHub Pages

### Step 1: Create a New Repository
1. Go to https://github.com/new
2. Name your repository (e.g., `plastics-recycling-map`)
3. Make it **Public**
4. **Do NOT** initialize with README, .gitignore, or license
5. Click "Create repository"

### Step 2: Upload Files
1. On your new repository page, click "uploading an existing file"
2. Drag and drop the `index.html` file from this folder
3. Or click "choose your files" and select `index.html`
4. Add a commit message like "Initial commit with Brokers layer"
5. Click "Commit changes"

### Step 3: Enable GitHub Pages
1. Go to your repository Settings
2. Click "Pages" in the left sidebar
3. Under "Source", select "Deploy from a branch"
4. Select branch: **main** (or **master**)
5. Select folder: **/ (root)**
6. Click "Save"

### Step 4: Access Your Map
After 1-2 minutes, your map will be live at:
```
https://YOUR-USERNAME.github.io/YOUR-REPO-NAME/
```

For example: `https://johndoe.github.io/plastics-recycling-map/`

## 📊 Data Sources

- MRF data: 440 facilities with capacity and location data
- Mills/Reclaimers data: 217 facilities geocoded from city/state information
- Brokers data: 8 commercial broker locations with 250-mile service radius

## 🎨 Interactive Features

- **Layer Control**: Toggle individual facility types on/off
- **Clickable Markers**: View detailed facility information
- **Legends**: Understand color coding and sizing
- **Fullscreen Mode**: Expand map to full screen
- **Measurement Tools**: Measure distances on the map

## 📝 License

Data visualization created October 2025
© 2025 Digital Industrial, Inc.

## 🔄 Updates

To update the map:
1. Replace `index.html` with the new version
2. Commit and push to GitHub
3. GitHub Pages will automatically update (may take 1-2 minutes)

