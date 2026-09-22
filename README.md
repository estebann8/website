# Esteban Salas Serrano — personal website

A plain HTML/CSS/JS site — no build tools, no dependencies. Open
`index.html` in a browser, or use VS Code's Live Server extension to
preview with auto-reload.

## Files

- `index.html` — content and structure
- `styles.css` — colors, type, and layout (see the tokens at the top)
- `script.js` — mobile menu toggle + auto-updating footer year

## Still to personalize

Search `index.html` for these and swap in your own details:

- `esteban@example.com` (two spots) — your real email
- `your-github` / `your-linkedin` — your real profile URLs
- The About section's second paragraph — what you actually spend time on
- The three `[Project name]` entries in the Work section — title, a real
  link in `href="#"`, and a one- or two-sentence description each. Delete
  entries you don't need, or copy the `<li>` block to add more.

## Customizing the look

The `:root` block at the top of `styles.css` holds the theme:
- `--accent` (muted purple) and `--accent-2` (cyan) — the two accent colors
- `--bg` / `--ink` / `--ink-soft` — background and text colors
- `--font-display` (JetBrains Mono) and `--font-body` (IBM Plex Sans)

## Publishing it with GitHub Pages

1. On the repo page, go to **Settings → Pages**.
2. Under **Branch**, choose `main` and `/ (root)`, then **Save**.
3. GitHub gives you a URL like `https://yourusername.github.io/repo-name`
   within a minute or two.

## Pushing updates

After editing files:
```
git add .
git commit -m "describe what you changed"
git push
```
