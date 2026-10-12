Foster Engineering website

HOW TO OPEN
Double-click index.html. No server or internet is needed (fonts load from Google when online).

HOW TO PUT ON A WEBSITE
Upload everything in this folder as it is (index.html, css/, js/, assets/).
All pages live inside index.html and are reached with # links (for example index.html#reference), so no special server settings are needed.

FILES
index.html        all pages and text
css/style.css     colours and layout
js/app.js         behaviour, language texts (TH/EN and 13 more), project and photo lists
assets/video/hero.mp4   Home background video for computers (loops, muted). Replace with your own file of the same name.
assets/video/hero-m.mp4 smaller copy of the video used on phones (about 0.7 MB). Replace it too if you change the video (854x480 is enough).
assets/logo.png         logo in the menu bar
assets/clients/         client logos
assets/img/             all other images (photos, brand logos, project pictures)

NOTES
- To change the Home video: replace assets/video/hero.mp4 (MP4/H.264, landscape, about 1280x720, under 5 MB, no sound needed).
- To change colours: edit the variables at the top of css/style.css (--navy, --red, --amber ...).

PHONES
The site is built to work on phones: the menu becomes a button (three lines) at the top right, cards stack in one column, the Home video uses the smaller file, and photos can be swiped left/right in the photo viewer.
