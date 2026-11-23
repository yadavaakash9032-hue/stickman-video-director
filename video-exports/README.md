# Video and image downloads

Open the [download index](DOWNLOADS.md) for every individual HTTPS file link. In Android Chrome, long-press a file link and select **Download link**. Find the saved file in Chrome's **⋮ → Downloads**.

This export contains 151 original media files (178,951,280 bytes). The opening MP4 and its decoded contact sheet are in this folder. The three character options are under `imagegen/`. Courier previews, completed frame and review exports, and project art are grouped separately. Incomplete intermediate encodes and bundled comparison references are excluded.

For future exports, place originals in a clearly named subfolder on the `video-downloads` branch, add their byte counts and SHA-256 hashes to the manifest, and update the index. Check GitHub's file limits before pushing and verify each raw HTTPS response against its original. Keep production files and `main` out of the export commit.
