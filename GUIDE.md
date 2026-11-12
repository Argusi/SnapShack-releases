# How to use SnapShack

- [The window](#the-window)
- [Browsing folders](#browsing-folders)
- [The viewer](#the-viewer)
- [RAW files](#raw-files)
- [Opening photos in your editor](#opening-photos-in-your-editor)
- [Deleting, moving, copying and renaming](#deleting-moving-copying-and-renaming)
- [Keyboard shortcuts](#keyboard-shortcuts)
- [Updates](#updates)
- [When something doesn't look right](#when-something-doesnt-look-right)

## The window

- **Folder tree** on the left: your Pictures folder and every drive. Click a folder to show its photos.
- **Toolbar** at the top:
  - **Open folder…** (Ctrl+O) picks any folder.
  - **Open in ▾** sends the selected photos to an editor.
  - **Include subfolders** shows the photos in every folder below this one too, as one list.
  - **Folder tiles** shows this folder's subfolders as tiles before the photos.
  - **Types ▾** chooses which kinds of files to show (see [Showing only some types](#showing-only-some-types)).
  - **Sort** by **Name** or **Date taken**, and **↑ / ↓** for the order.
  - **Size** sets how big the thumbnails are. **Ctrl + mouse wheel** over the grid does the same.
  - **ⓘ** (or **I**) shows the selected photo's details beside the grid: date, camera, lens, exposure and more. With several photos selected it shows how many and their total size.
  - **?** has the guide, updates and the version.
- **Status bar** at the bottom: how many photos there are, and while thumbnails are being made, how far along that is.

SnapShack remembers the folder, size, sort and toggles for next time.

## Browsing folders

The first time you open a folder, SnapShack makes a thumbnail of every photo in it. The ones on screen come first. After that the folder opens instantly, and only photos that are new or have changed get a new thumbnail.

Badges on a thumbnail tell you what it is:

- **RAW**, **PSD**, **HEIC**: the file type.
- **ON1**: the photo has an ON1 edit file (`.on1`) next to it, so you've edited it in ON1 Photo RAW.

Some tiles say why there's no picture:

- **Can't read this file**: the file is damaged, or isn't the type its name says. SnapShack skips it and carries on.
- **No preview: saved without "Maximize Compatibility"**: a Photoshop file saved without its flattened preview. Open it in Photoshop and save it again with **Maximize PSD and PSB File Compatibility** turned on.

The grid keeps up with the folder: when you (or your editor) add, change, rename or delete photos, the grid shows it within a second. **F5** refreshes it by hand, which is handy on network drives.

### Include subfolders

With **Include subfolders** on, the grid shows the photos in the folder and in every folder below it. Sorting by name keeps each folder's photos together. Sorting by date mixes them all in the order they were taken, which is a good way to see a whole year at once.

### Folder tiles

With **Folder tiles** on, subfolders appear as tiles at the start of the grid, each with a photo from inside it. Double-click a folder tile (or press Enter) to open it, and press **Backspace** (or Alt+↑) to go back up.

### Showing only some types

**Types ▾** on the toolbar has a tick for each kind of file: RAW, JPEG, PNG, TIFF, HEIC and PSD / PSB. Untick the ones you don't want to see. **Hide JPEGs that have a RAW** keeps the RAW and hides the JPEG when your camera saved both (IMG_0001.NEF next to IMG_0001.JPG). **Show all types** turns the filter off.

While a filter is on, the button says **Types (filtered)** and the status bar says how many photos it's hiding. SnapShack remembers it for next time.

## The viewer

Double-click a photo, or select it and press **Enter**.

- **Flip:** ← and → (also Space and Backspace, Page Up and Page Down, Home and End, the ‹ › buttons, or your mouse's back and forward buttons). The photos either side are already loaded, so flipping is instant.
- **Zoom:** the mouse wheel zooms in and out around the pointer. Drag to look around.
- **100%:** **Z**, a double-click or the zoom button switches between fitting the window and 100% (one photo pixel per screen pixel). **0** fits it again.
- **Fullscreen:** **F**. The top bar and the arrows hide; move the mouse to the top or the sides to get them back.
- **Info:** **I** or the **ⓘ** button opens a panel beside the photo: when it was taken, its size, the camera and lens, shutter speed, aperture, ISO and the rest, plus GPS position, artist and copyright when the camera saved them. It stays open as you flip until you close it. It's the same switch as the grid's ⓘ: on in one is on in both.
- **Back to the grid:** **Esc** or **← Grid**. The photo you were looking at is selected.

When you zoom in past the picture the viewer loaded, it loads the full resolution in the background. "Loading full resolution…" shows in the top bar, and the picture sharpens in place when it's ready.

## RAW files

RAW files contain a JPEG preview the camera made when you took the photo. SnapShack shows that, so browsing RAWs is as fast as browsing JPGs.

- **Most Nikon cameras** store a full-size preview, so even 100% is instant.
- **Fujifilm cameras** store a smaller preview. Zooming in past it decodes the RAW itself, which takes a few seconds (X-Trans files are slow to decode).
- **Very old cameras**, like the Nikon D1 series, store only a tiny preview, so SnapShack decodes the RAW. Their thumbnails take a moment the first time.

A RAW decoded on its own looks darker and flatter than the camera's preview, because it has none of the camera's picture style. That's very noticeable if you underexpose to protect the highlights. SnapShack copies the preview's brightness and colour onto the decoded RAW, so the picture only gets sharper when the full resolution arrives. Highlights the camera clipped stay clipped, as in the preview; use your RAW editor to pull them back.

## Opening photos in your editor

Select one or more photos, then:

- right-click and choose **Open in ON1 Photo RAW** (or another editor), or
- use **Open in ▾** on the toolbar, or
- press **Ctrl+E** for the first editor in your list.

In the viewer, right-click the photo or press Ctrl+E. The same menu has **Show in Explorer** and **Copy file path**.

The first time it starts, SnapShack looks for ON1 Photo RAW (the newest year you have), PhotoCraft, Photoshop and Lightroom Classic, and adds the ones it finds. **Editors…** at the bottom of the menu changes the list:

- **Add editor** adds any program.
- **Browse…** picks a program's `.exe`.
- **↑** moves an editor up. The first one opens with Ctrl+E.
- **✕** removes it.
- **Find installed editors** looks again, for example after you install Photoshop.

Lightroom Classic imports a photo it's given into its catalogue, rather than just opening it.

When an editor saves its result as a new file next to the original (ON1 does), the new file appears in the grid straight away.

## Deleting, moving, copying and renaming

Select photos in the grid (or look at one in the viewer), right-click, and choose:

- **Rename…** (**F2**): one photo at a time. The extension stays the same.
- **Move to** and **Copy to**: pick **Choose folder…**, or one of the last few folders you used.
- **Delete** (**Del**): moves the photos to the Recycle Bin, after asking. If the drive has no Recycle Bin (some network drives), Windows warns you that the files will be deleted for good.

### Drag and drop

Drag photos from the grid onto a folder in the tree on the left, or onto a folder tile. It works like Explorer:

- To a folder on the **same drive** the photos **move**; to **another drive** they're **copied**.
- Hold **Ctrl** to copy instead, or **Shift** to move. The status bar says which will happen before you let go.
- Or drag with the **right** mouse button: when you let go, SnapShack asks **Move here**, **Copy here** or **Cancel**. The one in bold is what a normal drag would do; Enter picks it.
- Hold the photos over a closed folder in the tree for a moment and it opens, so you can go deeper. Drag near the top or bottom of the tree to scroll it.
- To drag several photos, select them first, then drag any one of them.

You can also drag photos **out** of SnapShack, into an Explorer window, onto the desktop or into an editor, and drag files **in** from Explorer: onto a tree folder, a folder tile, or the grid itself (the folder that's open).

These use Windows' own file copying, so you get Explorer's progress window for big copies and its "replace or skip" question when a file is already there. Explorer's **Undo** (Ctrl+Z in an Explorer window) works on them too.

**Edit files go with their photo.** ON1's `.on1` file and an `.xmp` file with the same name are moved, copied, renamed and deleted along with the photo. When two photos share a name (IMG_0001.NEF and IMG_0001.JPG) and you only move one, the edit files stay with the one left behind.

## Keyboard shortcuts

| In the grid | |
|---|---|
| Enter or double-click | View the photo, or open the folder tile |
| Ctrl+E | Open in the first editor |
| I | Photo info beside the grid |
| F2 | Rename |
| Del | Delete (to the Recycle Bin) |
| Ctrl+O | Open folder… |
| Ctrl + mouse wheel | Thumbnail size |
| Backspace or Alt+↑ | Go up a folder |
| F5 | Refresh the folder |
| Ctrl+A | Select all |

| In the viewer | |
|---|---|
| → ← (Space, Backspace, Page Up/Down) | Next / previous photo |
| Home / End | First / last photo |
| Mouse wheel | Zoom around the pointer |
| Z, 1 or double-click | Fit ↔ 100% |
| 0 | Fit |
| F or F11 | Fullscreen |
| I | Photo info |
| Ctrl+E | Open in the first editor |
| F2 / Del | Rename / delete |
| Esc | Back to the grid |

## Updates

**? → Check for updates** asks GitHub whether there's a newer SnapShack. If there is, SnapShack asks before downloading anything, checks the download, and restarts on the new version. Your thumbnails and settings are kept. SnapShack also checks quietly once a day when it starts, and tells you in the status bar when there's an update.

## When something doesn't look right

- **A thumbnail looks wrong or old:** press F5. If it's still wrong, delete `%LocalAppData%\SnapShack\thumbs.db` and SnapShack rebuilds every thumbnail as you browse.
- **An error:** details are in `%LocalAppData%\SnapShack\snapshack.log`.
- **Start over:** quit SnapShack and delete the `%LocalAppData%\SnapShack` folder. Your photos are never touched.
