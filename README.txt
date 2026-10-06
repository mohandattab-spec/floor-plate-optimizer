FLOOR PLATE RAW MATERIAL OPTIMIZER – WEB APP

Files:
- index.html              Main optimizer
- manifest.webmanifest    Optional install-to-home-screen metadata
- sw.js                   Basic same-origin offline caching after first visit

Features in this version:
- Up to 40 floor-plate requirement rows; each row can have any Qty
- Excel upload (first worksheet; Part#, Length, Width, Qty and optional Part Weight)
- Raw-material Part# master and availability
- 1/4-in steel defaults: thickness 0.250 in, density 0.2830 lb/in^3
- ProNest-style base kerf default 0.091 in
- Edge trim, rotation, cost and optimization priority
- Best Material Plan with raw-material Part# and quantities
- Per-nest plate dimension, nest bounding dimension, plate weight, part weight, scrap weight,
  utilization, kerf and total parts
- Horizontal cutting diagrams
- PRINT / SAVE PDF

Important:
- Excel upload currently loads SheetJS from the SheetJS CDN, so Excel import requires internet access.
- The optimizer is a rectangular-envelope planner. It does not perform CAD/irregular contour/hole nesting.
- For production cutting, verify the final nest in ProNest/CAM.

GitHub Pages:
Upload index.html, manifest.webmanifest and sw.js to the repository root and deploy from main / root.
