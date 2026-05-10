# startblanck

A tiny, single-file mind-map / whiteboard.

- Plain white board (no grid)
- Text, image, and checkbox nodes
- Free-form arrows with draggable waypoints
- Pan, zoom, drag-and-drop images, image lightbox
- Right-click menu, marquee box-select, multi-select
- All data is saved automatically to your browser's `localStorage`

## Use

Open `index.html` in any modern browser. That's it.

### Controls

| Action | Shortcut |
|---|---|
| Open menu | **right-click** anywhere |
| Move a node | drag it |
| Move many nodes | select them, then drag any one |
| Pan the canvas | hold **Space** + drag |
| Zoom | mouse wheel |
| Box-select | drag empty area |
| Add to selection | **Shift** + click / **Shift** + drag |
| Select all | **Ctrl + A** |
| Draw an arrow | hold **Ctrl** + drag |
| Bend an arrow | drag any of its dots |
| Add a waypoint | double-click an arrow line |
| Remove a waypoint | double-click the dot |
| Edit text / checkbox label | double-click |
| Open image (zoom & pan) | double-click the image |
| Bring selection forward | **↑** |
| Send selection backward | **↓** |
| Delete selection | **Delete** |
| Deselect / close menu | **Esc** |

## Deploy on Vercel

This is a static site (no build step).

1. Push the repo to GitHub.
2. Import the repo on Vercel — when asked for a framework choose **Other**.
3. Leave Build Command empty and Output Directory empty (root).
4. Deploy.

`vercel.json` is included with sensible defaults.
