LORRY SPRAY HOUSE AR - VERSION 2
================================
Files (keep them together in one folder):
  index.html           main AR page (two-point alignment)  - Android Chrome
  app.js               the program for index.html
  site.glb             the model (spray house, ramps, tanks, lorry, spray)
  viewer.html         simple viewer for iPhone
  site_simple.glb      model used by viewer.html
  model-viewer.min.js  library used by viewer.html

TO UPDATE YOUR GITHUB SITE (you already have a repository):
  1. Open your repository on github.com. Click Add file > Upload files.
  2. Drag in ALL 6 files above (not the README, it is optional).
     When GitHub says a file already exists, that is fine: it replaces it.
  3. Click Commit changes. Wait 1-2 minutes.
  4. You can delete the old files spray_house_with_lorry.glb and spray_house_only.glb.
  5. Open your same link on the phone. If you still see the old page, close the tab and open it again.

ON SITE (Android, Chrome):
  1. Open the link, tap "Start AR on this phone", allow the camera.
  2. Tab "1 Align": pick two corners of the slab (default 1 and 2). Look at the small plan:
     corner 1 and 2 are on the pump-room side.
  3. Find the same two spots on the real ground (mark them with paint, cones or tape).
  4. Stand at the first spot, aim the + circle at it, tap "Set A here".
  5. Walk to the second spot, aim the + at it, tap "Set B here".
     The model snaps onto both spots and sits on the ground. The page shows how many cm the
     real distance differs from the drawing.
  6. Tab "2 Fine tune": move or turn the model in small steps, or switch on finger dragging.
  7. Tab "3 View": make the model see-through, drive the lorry, hide the lorry.

TIPS
  - Keep the two spots far apart (the long side, 5 m, is best).
  - Phone tracking drifts a little when you walk far. If the model slips, tap "Start again".
  - Press the X at top right to leave AR.
  - "Practise on this screen" lets you try the buttons on a phone or computer without the camera.
