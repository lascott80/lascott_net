# lascott.net

Static personal landing page for Lawrence Scott.

## Preview

Run a local static server from this directory:

```sh
python3 -m http.server 8020
```

Then open `http://localhost:8020/`.

## Assets

- `profile.jpg` and `profile.png` are the profile portrait sources used on the page.
- `og-image.jpg` is the social sharing preview image referenced by Open Graph and Twitter metadata.
- `favicon.svg`, `favicon-32.png`, `apple-touch-icon.png`, `icon-192.png`, and `icon-512.png` make up the browser, bookmark, and web app icon set.

## Notes

The page is plain HTML and CSS with one small progressive-enhancement script for desktop pointer movement. Touch devices and reduced-motion users get the static layout.
