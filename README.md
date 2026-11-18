# threads-media

Public images for @poorav.digital Threads posts.

- `YYYY-MM-DD/`: generated post images.
- `sales/`: sales notification screenshots for celebratory posts, with `sales/manifest.json` (count and times read from each image).

Adding screenshots: drop new images into `sales/`. The daily task reads any image not in the manifest, crops out buyer emails or names, and adds it.
