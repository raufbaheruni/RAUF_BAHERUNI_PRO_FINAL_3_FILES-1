# RAUF BAHERUNI — Instagram Spin View Prep

Professional GitHub Pages-ready photo converter for preparing a portrait JPEG for Instagram Stories.

## Upload only these 3 files to the repository root
- `index.html`
- `README.md`
- `rauf-baheruni.jpg`

**No assets folder is required.**

## What this version does
- Converts the selected photo to **3024 × 4032 JPEG**.
- Removes source metadata/GPS by redrawing the image.
- Adds a small compatibility EXIF profile using PiexifJS loaded from a public CDN.
- Provides **Download for Instagram** and **Share / Save** on supported phones.
- Keeps the interactive perspective Spin Studio and 1080 × 1920 Story video export.
- Runs photo processing in the browser; the site does not upload photos to a server.

## Important Instagram limitation
This tool prepares the file as closely as a browser-side converter can, but Instagram controls its own Spin View/glasses experience. A downloaded JPEG, EXIF fields, or a direct share from a website **cannot guarantee** that Instagram will display the proprietary Spin View effect. Official Ray-Ban Meta sharing to Instagram Stories is handled through Meta's glasses/Meta AI sharing flow.

### Posting workflow
1. Tap **CONVERT FOR INSTAGRAM SPIN VIEW**.
2. Use **Download for Instagram** or **Share / Save**.
3. Open Instagram → Story and select the converted JPEG.
4. If Instagram offers the Spin View/glasses experience for that account/media, use it there.

This is an independent utility and is not affiliated with Meta, Ray-Ban, or Instagram.
