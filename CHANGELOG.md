# Changelog

## [Unreleased]

## [0.7.0] - 2026-11-14

- Folder tree: your Windows Pictures folder now shows the name Windows gives it, marked "(Windows)", with a line between it and the drives, so it no longer looks like a favorite of the same name. Drives, USB sticks, network and cloud drives and favorites have their own icons.
- The Pictures folder can be hidden: right-click it → Hide Pictures folder, or View ▾ → Show Pictures folder.
- A slow or sleeping drive no longer freezes the window: the folder tree reads folders in the background and shows "Loading…" until the drive answers. Adding a favorite on such a drive no longer hangs either.

## [0.6.1] - 2026-11-13

- Videos: pausing right after pressing Play, or scrubbing a paused video (also after it reached the end), now shows the right frame instead of a frozen or blank picture.
- Faster thumbnails in big folders: cached thumbnails no longer wait while new ones are being saved, and Include subfolders reads the cache much faster.

## [0.6.0] - 2026-11-13

- GIFs: still and animated GIFs show in the grid (with a GIF badge) and in View ▾ → Types. Animated ones play in the viewer, looping; Space pauses and plays them. Zoom and pan work while they play.
- Icons: .ico files show in the grid (ICO badge) and viewer at the biggest size inside, with their transparency, and have their own Icons group in Types.

## [0.5.0] - 2026-11-13

- Videos: MP4, MOV, AVI, MTS/M2TS, MPG, 3GP, WMV, M4V and MKV show in the grid with a frame from the clip and its length, sort by the date they were filmed, and play in the viewer: Space or a click to play and pause, a bar to scrub, 5-second jumps (Shift+← / →), frame steps (, and .), volume and mute. Zoom works while they play. Old camera clips (AVI, Motion JPEG, MPEG) and phone HEVC all play; nothing extra to install.
- Video speed: hold the mouse button on a playing video for 2×, or Ctrl+wheel (Shift+< / Shift+>) from 0.25× to 4×.
- Copy a video frame: Ctrl+C in the viewer copies the frame on screen as a picture. In the grid, Ctrl+C copies the video file.
- View ▾ → Types has a Videos group, and the info panel shows a video's length, codec and frame rate.
- Videos are listed under Explorer's Open with too (an existing setting is updated by itself).

## [0.4.0] - 2026-11-12

- Screen saver: SnapShack can be your Windows screen saver, a random slideshow of the folders you choose (and all their subfolders) on every monitor. Add it to Windows' screen savers in ⚙ Settings (or the setup), then pick it in Windows' Screen Saver dialog.
- Slideshow (S): the grid's photos full screen with a fade, from the selected one. Space pauses, arrow keys step and change the speed, 1-9 rate as it plays. Speed, random order and the caption are in ⚙ Settings.
- SnapShack remembers where you were: coming back to a folder selects the photo you were on there, closing in the viewer reopens it on that photo, and Back / Forward folder history is kept between sessions.
- Favorite folders at the top of the folder tree: right-click a folder → Add to Favorites, or Ctrl+D for the open one.
- Map (M, or View ▾ → Map): the photos with a GPS location on an OpenStreetMap map, grouped into numbered circles; click one to see those photos. Needs an internet connection for the map itself.
- Compare: select 2-4 photos and press C (or right-click → Compare) to see them side by side, zoomed and moved together, to pick the sharpest of a burst. Rate the picked one with 1-5 as you go.
- Ratings and color labels: 1-5 stars (0 clears) and 6-9 for Red, Yellow, Green, Blue, in the grid and the viewer, or right-click. Shown on the thumbnails; View ▾ → Rating / Label shows only some. Saved in .xmp sidecars next to the photos (the photos themselves never change), which ON1 and Lightroom read; ratings already in your photos show too. In the viewer, 100% is now Z or Ctrl+1 and Fit is Ctrl+0, because the number keys rate.
- The mouse's back and forward buttons (and Alt+← / Alt+→) go back and forward through the folders you've visited, like in Explorer. In the viewer they still flip photos.
- Tidier toolbar that fits a small window: sort, Include subfolders, Folder tiles and Types are now under View ▾, the search box narrows with the window, and ⓘ, Settings and ? always stay in view.
- Always on top (View ▾), remembered.
- ⚙ Settings: editors, color matching, the daily update check (now can be turned off) and file types in one place.
- Open photos from Explorer: SnapShack is listed under Open with for every photo type it reads, and folders get Browse with SnapShack. To make it the default for a type, use Explorer's Open with → Always; ⚙ Settings shows which app opens each type. A photo opens in the viewer in its folder, in the SnapShack window that's already open.
- Copy image (Ctrl+C, or right-click): copies the photo so you can paste it into email, chat, Word or KlipShot (as an sRGB picture up to 4000 pixels on its long edge). With several photos selected, the files are copied, to paste into Explorer or attach to an email.

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
