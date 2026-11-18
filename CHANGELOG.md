# Changelog

## [Unreleased]

## [0.9.0] - 2026-11-17

- Printing. **Print…** in the toolbar (or right-click, or Ctrl+P) opens a page layout for the selected photos, or the one in the viewer:
  - Pages at your printer's real paper size, with the edge it can't reach shown dashed. Choose the printer, paper, orientation, margins and spacing, and open the printer's own settings for paper type, quality and borderless.
  - Drag photos from the strip onto the page. Move them (they snap into line), resize them from a corner or with the mouse wheel, type an exact size like 5x7, show the whole photo (Fit) or crop it to fill its frame (Fill), turn a print, duplicate it, and drop one photo on another to swap them.
  - Cells: 1, 2, 4, 6 or 9 per page, or your own grid, for this page or all the photos. Empty cells are slots to drop photos into. Put all here and Arrange lay a page out for you.
  - A sharpness badge on every photo (green, amber, red by its print resolution), and warnings before printing a soft photo or one past the printer's edge.
  - Several pages, Undo and Redo, and your layout is kept until SnapShack closes. Your printer, its settings and margins are remembered.
  - RAW files print from full resolution, never the small preview, sent at the printer's photo resolution (300 ppi, 360 for Epson).
- Buttons that can't be used at the moment now look greyed out, everywhere in SnapShack.

## [0.8.6] - 2026-11-15

- SnapShack.exe, the setup and the uninstaller are now code-signed: Windows shows the publisher as Bruce David Maloney instead of "Unknown publisher". Microsoft Defender and SmartScreen should warn less often as the signature builds up trust.

## [0.8.5] - 2026-11-15

- ? → How to use SnapShack (F1) opens the guide online, with its screenshots and always up to date, instead of the copy next to SnapShack.exe (which stays there to read offline).
- New ? → What's new opens this list of changes.
- The README and the guide now explain the Microsoft Defender warnings: they're false alarms on a new, unsigned app, and code signing is in progress.

## [0.8.4] - 2026-11-15

- No changes you'll notice: a rebuild so the version information inside SnapShack.exe names the exact source it was built from.

## [0.8.3] - 2026-11-15

- The mouse's forward button (or Alt+→) now undoes the back button: after going back from the viewer to the grid, forward opens the viewer again on the same photo. The same goes for Compare and the map. Once there is nothing to reopen, forward moves on to the next folder as before.
- The back button (or Alt+←) also closes Compare and the map now, and works in the map itself.

## [0.8.2] - 2026-11-14

- Updates no longer go through Windows' Temp folder: SnapShack downloads them into an "update" folder inside its own folder and swaps in the new SnapShack.exe, installed copies too (they used to run the setup). If your antivirus wrongly flags SnapShack, one exclusion for SnapShack's folder (normally %LOCALAPPDATA%\Programs\SnapShack) now covers updates as well. Windows' Apps list keeps showing the right version.

## [0.8.1] - 2026-11-14

- A selected folder tile is remembered like a photo: coming back to the folder (or starting SnapShack) selects that tile instead of jumping to the last photo you had selected.

## [0.8.0] - 2026-11-14

- Search finds folders too: with Folder tiles on, a search shows the subfolders whose name matches as tiles. With Include subfolders on as well, it finds matching folders at any depth below the open folder (shown by their path, such as Trips\Paris 2019). Opening a found folder clears the search. While Folder tiles is on, a folder's name finds only its tile: the photos and videos inside show only if they match by their own name, camera, lens, keywords or date.
- Going back to a search: after opening a folder found by a search, Back (Backspace, Alt+← or the mouse's back button) returns to the search with that folder selected, ready to pick the next one.
- Viewer: the mouse's back button now returns to the grid (like Esc) instead of flipping to the previous photo.
- Recent searches: click into the empty search box (or press ↓ in it) for your last 10 searches. A search is remembered when you clear it, leave the box, or open a photo or folder from it.

## [0.7.1] - 2026-11-14

- Folder tree: selecting a folder with a long name no longer scrolls the tree sideways and hides its left edge, and the stray bar and white square at the bottom of the tree are gone.

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
