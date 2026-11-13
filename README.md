# EXPLORE IDUKKI — Tourism & Travel Guide

A responsive, front-end tourism website demo built with HTML, CSS and vanilla JavaScript.

## Files
- `index.html` — page structure and content
- `style.css` — responsive visual design
- `script.js` — destination search/filter, favourites, detail modal, trip planner, gallery lightbox and navigation
- `README.md` — setup and deployment notes

## Run locally
1. Download and extract the ZIP.
2. Open `index.html` in a browser.
3. For a local development server, open the folder in VS Code and use the Live Server extension.

## Publish with GitHub Pages
1. Create a GitHub repository (for example, `explore-idukki`).
2. Upload all four files to the repository root.
3. Open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then Save.
6. Wait for GitHub Pages to publish your site.

## Important project notes
- This is a static front-end demo. It does not include a real database, user accounts, admin authentication, or message submission backend.
- Favourites are held only in the current page session and are not synced or permanently stored.
- The trip planner creates a sample itinerary in the browser; it does not check live availability, routes, permits or opening hours.
- Accommodation entries are clearly labelled sample listings. Do not treat them as real properties, prices or contact details.
- Images are loaded from Unsplash URLs and Google Fonts from their hosted services; internet access is needed for these assets.
- The embedded map uses OpenStreetMap. Google Maps links open directions/search in a new tab.
- Check all destination access, seasonal restrictions, permits and safety guidance with official/local sources before travel.

## Customise
Edit the `destinations` array near the top of `script.js` to change destination descriptions, categories, locations and image URLs. Update the accommodation sample cards directly in `index.html`.
