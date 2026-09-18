# wyss-520.github.io

Static academic homepage for `https://wyss-520.github.io/`.

## Preview locally

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Customize

Most content is in `index.html`. Replace the visible placeholder text for:

- name, position, institution, location, email, Scholar, and CV;
- biography and research interests;
- news;
- publications and paper links;
- experience, education, awards, and service.

Put paper thumbnails and other images in `assets/images/`. Styling is in
`assets/css/style.css`; the small mobile-navigation script is in
`assets/js/main.js`.

## Publish

Create a public GitHub repository named `wyss-520.github.io`, push this directory
to its `main` branch, and select **Deploy from a branch** in
**Settings → Pages** if Pages is not enabled automatically.
