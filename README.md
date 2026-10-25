# Standard Chaos Studio website

Live and let live. 🐩🐩

## Adding a new piece (about 2 minutes, all on github.com)

**1. Upload the image**

1. Open the **`art`** folder in this repo.
2. Click **Add file → Upload files**.
3. Drag in your watermarked image. Simple names work best: `sunday-zoomies.jpg` (lowercase, dashes, no spaces).
4. Click **Commit changes**.

**2. Add it to the gallery**

1. Open **`gallery.txt`** and click the ✏️ pencil icon.
2. Add a block like this, with an empty line above it:

   ```
   Sunday Zoomies
   file: sunday-zoomies.jpg
   caption: Gouache on paper, 18 × 24 in.
   status: Available
   ```

3. Click **Commit changes**.

The website updates on its own in about a minute. Refresh to see it.

## Quick reference

| Line      | What it does                                   | Required? |
|-----------|------------------------------------------------|-----------|
| (first)   | Title of the piece                             | Yes       |
| `file:`   | Image name in the `art` folder                 | No        |
| `year:`   | Shown under the title                          | No (defaults to 2026) |
| `caption:`| Shown when someone opens the piece             | No        |
| `status:` | Little tag on the image: Available, Sold, New… | No        |

- **Change a title or caption:** edit the words in `gallery.txt`, commit.
- **Reorder:** move blocks up or down. The site follows the file's order.
- **Remove a piece:** delete its block (and the image, if you like).
- **Image tips:** JPG, around 2000px on the long side, under 1 MB. Watermark before uploading. Landscape images fill the tiles best; every image shows in full when clicked.

## Files

- `index.html` – the website (no need to touch it)
- `gallery.txt` – the gallery list (edit this)
- `art/` – the images
