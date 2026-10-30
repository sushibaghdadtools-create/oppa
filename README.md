# Oppa Client Portal

A home page where a client enters a 6-digit access code and then sees the **Your Growth Partner** presentation.

## Put it live on GitHub Pages

1. Create a new **public** repository on GitHub (for example `oppa-portal`).
2. Upload **everything in this folder**, keeping the `assets` folder and the `.nojekyll` file.
3. In the repository go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**, branch **main**, folder **/ (root)**, then **Save**.
5. After a minute or two the portal is live at `https://<your-username>.github.io/oppa-portal/`.

To use your own domain (for example `portal.oppa.com`), add it under **Settings → Pages → Custom domain**.

## Using it

- The access code is set when the site is built; it is not stored in the files.
- After the code: ← → arrow keys, space, swipe or tap to move between slides. The lock button returns to the home page.

## Good to know

- The slides are encrypted inside `index.html` and only open with the right code. This keeps casual visitors out, but it is not bank-grade security: someone technical could try every 6-digit code. Don't put anything highly confidential in it.
- To change the code or the slides, the site has to be rebuilt. Ask Claude and upload the new `index.html`.
