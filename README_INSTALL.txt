CTP Intermediate Fix Assets

Upload these files in the repository ROOT:
- styles.css
- app.js
- ctp_places_data_intermediate.js
- logo_ctp.png
- favicon.png

These files are the missing assets that made the intermediate release appear broken:
- no layout
- no cards
- no visible data rendering
- no logo
- no map data file

ORDER:
1. Upload all 5 files in the repository root
2. Commit directly to main
3. Wait for Vercel deploy
4. Test:
   /index.html
   /cities.html
   /places.html
   /map.html
   /florence.html
   /rome.html
