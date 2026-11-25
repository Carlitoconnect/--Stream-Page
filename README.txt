# Carlito Connect Stream Page

A simple mobile-friendly landing page for your Carlito Connect stream.

## Files and folders

- `index.html` — page structure
- `style.css` — black and red styling
- `images/top-banner.png` — the image shown in the top panel; replace this with your own image
- `images/carlito-logo.png` — your Carlito Connect mascot logo
- `videos/stream-intro.mp4` — add your own introduction video here

## Add your own image to the top panel

1. Open the project folder, then open the `images` folder.
2. Replace `top-banner.png` with your own image.
3. Give your image the exact filename `top-banner.png` (make sure Windows has not added `.jpg` or another extension).
4. Refresh the website. The image will fit inside the top red-bordered panel without being stretched.

You can use a PNG, JPG, or WebP image. If your image is a JPG or WebP, either save/export it as PNG named `top-banner.png`, or change the filename in the `src` line in `index.html` to match your image.

## Add your video

1. Put your MP4 video in the `videos` folder.
2. Name it `stream-intro.mp4`.
3. The video player is already set up in the middle panel.

## Start the site on Windows

**Quickest method:** open the project folder and double-click `index.html`. It should open in your browser.

**Recommended method in VS Code:**
1. Open VS Code.
2. Choose **File → Open Folder** and select `carlito-connect-stream`.
3. Install the **Live Server** extension if you do not already have it.
4. Right-click `index.html` and choose **Open with Live Server**.
5. Your browser will open the page. Save changes in VS Code and the browser will refresh.

## Publish with GitHub Pages

1. Create a new GitHub repository named `carlito-connect-stream`.
2. Upload the contents of this folder (the files inside it, not the ZIP).
3. In the repository, open **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch `main` and folder `/ (root)`, then save.
6. Wait for GitHub Pages to publish. Your address will look like:
   `https://YOUR-USERNAME.github.io/carlito-connect-stream/`

You can then point your printed QR code at that published address.

## Editing stream details

Open `index.html` and change `Monday 9.30pm`, `Rip N Ship`, or `eBay Live` to update the details.
