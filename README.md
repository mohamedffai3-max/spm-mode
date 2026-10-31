# SPM MODS — Front-end

Static front-end prototype for GitHub Pages.

## Files
- `index.html` — Home, all mods, categories, about, and mod details pages.
- `style.css` — Responsive dark/black and red design.
- `script.js` — Interactive edition switch, search, category filters, sorting, View All pages, mod details, similar mods, and trailer modal.

## Run
Open `index.html` in a browser, or upload all files to a GitHub repository and enable **Settings → Pages → Deploy from a branch → main → / (root)**.

## Add/edit mods
Edit the `mods` array near the top of `script.js`. Each item supports:
- `name`, `category`, `edition` (`Java` or `Bedrock`)
- `version`, `size`, `downloads`, `description`
- `download`: direct download URL
- `video`: YouTube embed URL, e.g. `https://www.youtube.com/embed/VIDEO_ID`

Categories: `Movement`, `Weapons`, `World`, `Mobs`, `Furniture`, `Tools`.

The current entries are demo data. Replace demo descriptions, links, versions, and download counts with real information. The trailer modal is a placeholder until a trailer URL is provided. This version has no database, admin dashboard, or file upload.
