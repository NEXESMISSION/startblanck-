# startblanck

A tiny, single-file mind-map / whiteboard.

- White board with a subtle dotted grid
- Text, image, and checkbox nodes
- Free-form arrows with draggable waypoints
- Pan, zoom, drag-and-drop images, image lightbox
- All data is saved automatically to your browser's `localStorage`

## Use

Open `index.html` in any modern browser. That's it.

### Controls

| Action | Shortcut |
|---|---|
| Move a node | drag it |
| Pan the canvas | hold **Space** + drag |
| Zoom | mouse wheel |
| Draw an arrow | hold **Ctrl** + drag |
| Bend an arrow | drag any of its dots |
| Add a waypoint | double-click an arrow line |
| Remove a waypoint | double-click the dot |
| Edit text / checkbox label | double-click |
| Open image (zoom & pan) | double-click the image |
| Add an image | toolbar button, or drag-drop a file / URL |
| Delete selected | **Delete** key |
| Clear everything | toolbar **Clear** button |

## Deploy on Vercel

This is a static site (no build step).

1. Push the repo to GitHub.
2. Import the repo on Vercel — when asked for a framework choose **Other**.
3. Leave Build Command empty and Output Directory empty (root).
4. Deploy.

`vercel.json` is included with sensible defaults.
