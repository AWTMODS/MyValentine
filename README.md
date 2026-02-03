My Valentine — Simple site with customizable background

What I added

- `index.html`: Minimal page that lets you preview an image URL or use the bundled background.
- `css/style.css`: Styles that apply a full-screen background via the `--bg-image` CSS variable.
- `assets/images/background.svg`: A lightweight placeholder background you can replace.

How to use

- To use your own image file, replace `assets/images/background.svg` with your image (keep the same filename), or edit `css/style.css` `:root` variable to point to another local path.
- To preview an external image quickly, open `index.html` in a browser and paste an image URL into the input, then click "Apply".

Upload and drag-and-drop

- Open `index.html` in a browser and use the "Or upload an image from your device" file input to select an image; the page will preview it locally using a data URL (the image is not uploaded anywhere).
- You can also drag an image file from your computer onto the page to set it as the background.

Base64 share links

- You can generate a client-only share link that embeds the selected image as a base64 data URL in the link fragment. Click "Generate Share Link" after uploading or dragging an image, then copy the link.
- Limitations: embedded links can become very large and may not work in some messengers, email clients, or services. For photos, prefer server-backed storage and short links.

Deploying to GitHub Pages

- Create a repository named `MyValentine` (or use the existing repository), push these files to the `main` branch, then enable GitHub Pages from the repository settings (site will be served from `main` branch root).

Need a custom image?

- If you want, provide the image file (or a URL) and I can add it for you and tweak the layout/colors to match the image.