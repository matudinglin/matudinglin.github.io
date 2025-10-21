Place your images in this folder.

How to show them on the Photos page:

1) Add the filenames to `photos/index.json`, for example:

[
  "trip-1.jpg",
  "trip-2.jpg",
  "concert.png"
]

2) Open `photos.html` in a browser. The thumbnails will be generated automatically and clicking them opens a lightbox.

Tips
- Large images are fine; lightGallery creates thumbnails from the <img> tags you see.
- Filenames are treated relative to this folder, so just use the file names (no path).
