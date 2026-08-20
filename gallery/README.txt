Drop group photos and video clips in this folder using these exact
filenames and they'll appear automatically in the scrolling Gallery
section. Until a file exists, that slot shows a labeled placeholder
tile -- nothing breaks, and you can add/remove slots any time by
editing the gallery section in index.html.

PHOTOS (.jpg, landscape works best, ~340x226px or wider):
gallery/group-1.jpg
gallery/group-2.jpg
gallery/group-3.jpg
gallery/group-4.jpg
gallery/group-5.jpg
gallery/group-6.jpg

VIDEOS (.mp4, short clips recommended):
gallery/clip-1.mp4   (thumbnail: gallery/clip-1-poster.jpg)
gallery/clip-2.mp4   (thumbnail: gallery/clip-2-poster.jpg)

Poster images are optional -- they're just the thumbnail shown
before someone presses play. If you skip them, the browser will
show the video's first frame instead once the file is uploaded.

To add MORE than 6 photos or 2 videos, copy one of the
<div class="gallery-item">...</div> blocks in the Gallery section
of index.html, give it a new filename, and paste it in the list --
or just ask and it'll be added for you.
