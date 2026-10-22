# BagaCAD documentation

Short English documentation for BagaCAD 0.22 Alpha. MkDocs + Read the Docs theme, published with GitHub Pages.

Site: https://antbaga.github.io/BagaCAD_Documentation/

## Edit locally

Edit the Markdown files in `docs/`. Navigation is in `mkdocs.yml`.

```powershell
python -m pip install -r requirements.txt
python -m mkdocs serve
```

Open http://127.0.0.1:8000. Changes reload automatically.

## Publish

```powershell
python -m mkdocs build --strict
git add .
git commit -m "Update documentation"
git push origin main
```

GitHub Actions builds and publishes to `gh-pages`. In the repository's **Settings > Pages**, the source is **Deploy from a branch**, branch **gh-pages**, folder **/ (root)**.

Do not edit generated files in `site/` or on `gh-pages`.

## Content

Document implemented behavior, not proposed shortcuts. Check the addon code when updating: its README may lag behind the current defaults. This edition uses the 0.22.0 manifest and the preference defaults in the local source.
