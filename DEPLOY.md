# Deploying the Balaji Wafers MAMSYS prototype on GitHub Pages

Upload the contents of this folder—not the folder itself—to the top level of the repository:

- `index.html`
- `.nojekyll`

Then open the repository on GitHub and go to **Settings → Pages**. Under **Build and deployment**:

1. Set **Source** to **Deploy from a branch**.
2. Select the branch containing these files, usually `main`.
3. Select the folder `/(root)`.
4. Click **Save**.

Wait for the Pages deployment to finish, then use the **Visit site** button in the same settings screen. Open that published `github.io` address—not the `github.com/.../blob/.../index.html` repository preview.

The site is a single self-contained HTML application. The Google Fonts request is optional; system fonts will be used if it is unavailable.

## Confidentiality warning

The `noindex` instruction in the HTML asks search engines not to index the page, but it does not make the site private. Treat a standard GitHub Pages deployment as publicly accessible unless your GitHub organization has explicitly configured private Pages access control.
