Stage Zero Configurator (MTZ)
=============================
GitHub Pages: upload everything in this folder to the repository root (or /docs), keep the folder names exactly as they are
(file names are case-sensitive), then enable Pages in Settings > Pages. All paths are relative, so it also works from github.io/<repo>/.

Local test (inside this folder):  python3 -m http.server 8000   ->   http://localhost:8000

Files
  index.html              the site (bonnet and door opening is built in, see the Open tab)
  favicon.ico             browser tab icon (16/32/48 px)
  assets/mtz-logo.png     MTZ logo, your original, cropped to its visible edges (aspect ratio 2.036:1 unchanged)
  assets/favicon-32.png, favicon-192.png, apple-touch-icon.png
  data/golf7-gti.glb      Golf 7 GTI model
  data/golf5-gti.glb      Golf 5 GTI model
  .nojekyll               tells GitHub Pages to serve files as they are

Three.js 0.160.0 loads from cdn.jsdelivr.net and fonts from Google Fonts, so internet access is needed.

Credits
  Golf 7 GTI: "Volkswagen Golf GTI MK7" by RPMRender (Sketchfab Standard license, check redistribution terms)
  Golf 5 GTI: "vw golf 5 gti" by giuffridanicolo54 (Sketchfab, CC BY 4.0, attribution required)
