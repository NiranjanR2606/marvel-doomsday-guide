MARVEL: THE ROAD TO AVENGERS — DOOMSDAY

Updated page changes
- Added “Created & curated by Niranjan · @niranjan__.r” directly below the main title.
- Added a cinematic creator-credit treatment with a clickable Instagram link.
- Added referrerpolicy="no-referrer" to the six Disney gallery image elements to reduce the chance of third-party hotlink blocking.
- Removed the external Disney image from the hero CSS background so the hero artwork area no longer depends on that image request.

IMPORTANT IMAGE NOTE
The gallery still requests the six promotional stills from Disney’s image CDN. The no-referrer change may resolve a referrer-based block, but it cannot guarantee image delivery if Disney blocks third-party embedding or the network blocks the CDN. The reliable option is to use image files that you are authorized to host in your own GitHub repository under /images, then point the image src values to those local files. Credit alone does not grant permission to redistribute Disney promotional images.

DEPLOY
Replace the repository’s root index.html with this updated index.html and commit the change. GitHub Pages will redeploy automatically.
