SMURF REFUGEE GUIDE — VS CODE SETUP

1. Keep index.html and the assets folder together in the same project folder.
2. Open the folder (not only the HTML file) in VS Code.
3. Recommended: install/use Live Server, then right-click index.html > Open with Live Server.
4. The page loads p5.js from a CDN and includes one YouTube embed, so those pieces need internet access.
5. All image files are local under assets/ instead of being embedded as giant base64 strings.

WHAT WAS FIXED
- Rebuilt the visual system for a cleaner survival-guide look.
- Images are responsive and intentionally sized (wide, portrait, medium, small).
- Removed malformed extra closing tags near the end of the original HTML.
- Rebuilt the Smurf language matcher as a responsive p5.js canvas game.
- Rebuilt the food-corridor p5 sketch to resize on smaller screens.
- Added a First 24 Hours arrival checklist with a progress bar.
- Added an emergency bell-signal drill.
- Added sticky section navigation and accessibility controls (larger text / reduced motion).
- Moved all 11 embedded images into an assets folder, shrinking index.html from ~22 MB to ~42 KB.

FILES
index.html
assets/
  logo-upscaled.png
  welcome-village.jpg
  ancestral-council.png
  forest-environment.png
  respect-matriarchy.png
  gargamel.png
  seasons.jpg
  corridors.jpg
  etiquette-1.jpg
  etiquette-2.png
  welcome-smurfs.png

If you change an image later, replace the corresponding file in assets/ and keep the filename the same.
