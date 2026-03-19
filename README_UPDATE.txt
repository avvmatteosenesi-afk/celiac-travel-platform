CTP Update Pack Combined v1

This package merges:
- the current intermediate release pages
- the missing assets/data fix required to make the site render correctly

ROOT FILES TO UPLOAD
Upload/replace these files in the repository root:
- index.html
- cities.html
- places.html
- map.html
- florence.html
- rome.html
- milan.html
- naples.html
- prato.html
- pistoia.html
- cinque-terre.html
- amalfi-coast.html
- capri.html
- lake-garda.html
- lake-como.html
- styles.css
- app.js
- ctp_places_data_intermediate.js
- logo_ctp.png
- favicon.png

LANGUAGE SUBFOLDERS
Upload/replace files inside:
- /it
- /esp
- /deu
- /fra

IMPORTANT
Do not create nested folders such as /it/it or /esp/esp.
Each language folder must contain its own files directly:
- /it/index.html
- /it/cities.html
- /it/map.html
- /it/places.html
(and same structure for esp, deu, fra)

SUGGESTED ORDER
1. Upload all root files first.
2. Commit directly to main.
3. Upload the four language folders contents.
4. Commit directly to main.
5. Wait for the Vercel deploy.
6. Test:
   /index.html
   /cities.html
   /places.html
   /map.html
   /florence.html
   /rome.html
   /it/index.html
   /esp/index.html
   /deu/index.html
   /fra/index.html

AFTER DEPLOY
Force refresh with ?refresh=1 if needed.
Example:
- /index.html?refresh=1
- /map.html?refresh=1
