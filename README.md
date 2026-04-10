# EezPlatforms Website

Static one-page site for `www.eezplatforms.com`.

## Files

- `index.html` page markup
- `styles.css` site styling
- `favicon.svg` site icon
- `CNAME` custom domain config
- `.nojekyll` disables Jekyll processing on GitHub Pages

## Local Preview

```bash
cd eezplatforms-web
python3 -m http.server 8080
```

Then open `http://localhost:8080`.

## GitHub Pages

1. Push this folder's contents to the repository root for the `eezplatforms-web` site.
2. In GitHub, open `Settings` -> `Pages`.
3. Set `Source` to `Deploy from a branch`.
4. Select `main` and `/ (root)`.
5. Confirm the custom domain is `www.eezplatforms.com`.
