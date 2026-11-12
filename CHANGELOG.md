# Changelog

## [Unreleased]

## [0.3.1] - 2026-11-12

- SnapShack remembers its window size and position (and whether it was maximized), like KlipShot. If that spot is off screen, for example after unplugging a monitor, it opens centered.

## [0.3.0] - 2026-11-12

- Search (Ctrl+F): find photos by file or folder name, camera, lens, keywords (including Lightroom/ON1 .xmp sidecars) or year, in the open folder or with all its subfolders. Phrases in quotes, -word to leave out, 1995-1999 for a range of years, 2019-06 for a month.
- The info panel shows a photo's keywords.

## [0.2.0] - 2026-11-12

- Accurate color: photos are shown in your monitor's color profile (as set in Windows' Color Management), and profiles embedded in photos (Adobe RGB, Display P3, ProPhoto) are honored everywhere, including PSD, HEIC and camera JPEGs shot in Adobe RGB. Switch it off under ? → Match colors to the monitor.
- Rotate (Ctrl+R / Ctrl+L, right-click, or the buttons in the viewer). JPEG and TIFF files get their orientation tag changed: the pictures are never re-saved, so nothing is lost. RAW, PSD, PNG and HEIC files aren't changed; SnapShack remembers their rotation.
- Export… (Ctrl+Shift+E): save copies as JPEG, TIFF, PNG, WebP, AVIF or JPEG XL, at the original size or by long edge, short edge, width, height, a box or a percentage, with optional sharpening, sRGB conversion, and metadata kept or removed (including location). RAW files export as the viewer shows them.
- Thumbnails are made again once, to pick up the color fixes.

## [0.1.0] - 2026-11-12

The first version.

- Folder tree and a fast thumbnail grid that stays smooth with tens of thousands of photos. Thumbnails are kept, so folders open instantly the next time.
- JPG, PNG, TIFF, HEIC, Nikon NEF, Fujifilm RAF, DNG, PSD and PSB. RAW files show the camera's own preview.
- Sort by name or date taken; thumbnail size slider and Ctrl + mouse wheel.
- RAW, PSD, HEIC and ON1 badges.
- Viewer: flip with the arrow keys, zoom and pan, 100%, fullscreen. Full resolution loads when you zoom in, and RAW files keep the camera's look.
- Open in ON1 Photo RAW, PhotoCraft, Photoshop or any editor, from the toolbar, a right-click or Ctrl+E.
- The grid follows changes to the folder, such as a new file your editor saves.
- Include subfolders, and folder tiles you can click through.
- Photo info beside the grid and in the viewer (I): camera, lens, exposure, size, GPS.
- Delete (to the Recycle Bin), move, copy and rename, with ON1 and XMP edit files kept alongside their photo.
- Drag and drop photos onto folders in the tree or folder tiles (move or copy, like Explorer; right-drag asks Move here / Copy here), out to Explorer and other apps, and in from Explorer.
- Types filter: show only some kinds of files, or hide JPEGs that have a RAW.
- Help → Check for updates.
