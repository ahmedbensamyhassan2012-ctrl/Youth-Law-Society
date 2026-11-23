# Youth Law & Society

A static, plain-language legal guide for young people. The site is a single-page
HTML app with four views: Home & Topics, Interactive Demos, Knowledge Quizzes,
and Legal Sources.

## Files

- `index.html` — the page structure
- `styles.css` — all custom styling
- `script.js` — topic data, quizzes, simulators, and page logic
- `images/` — the 12 topic illustrations used by the cards, modals, scenarios, and quizzes
- `.nojekyll` — tells GitHub Pages to serve the files exactly as they are

Keep all four items together in the same folder. The image and file paths are
relative, so the structure must stay the same.

## Publish with GitHub Pages

1. Create a new public repository on GitHub.
2. Upload `index.html`, `styles.css`, `script.js`, the `images` folder,
   `README.md`, and `.nojekyll` to the repository root.
3. Open the repository's **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select branch **main** and folder **/ (root)**, then click **Save**.
6. Wait a minute or two. The site will appear at:

   `https://YOUR-USERNAME.github.io/REPOSITORY-NAME/`

## Editing

- Page text and layout: `index.html`
- Colors, spacing, and typography: `styles.css`
- The 12 topic entries and quiz data: `script.js` (the `modulesData` array)
- Topic pictures: `images/`

No build step is required.
