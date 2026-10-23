# Pendulum X / D-cyber 中文攻略

DigiKidult fan guide. A static GitHub Pages website exported from the source workbook `Pendulum X _ D-cyber 中文攻略.xlsx`. The original spreadsheet was not modified.

## Publish

1. Extract this zip into a GitHub repository root.
2. Under Settings → Pages, select **Deploy from a branch**, branch `main`, folder `/ (root)`.
3. Open the URL GitHub Pages provides. No backend or API keys required.

## Contents

- `index.html`, `style.css`, `app.js`: website files
- `data.json`: source sheet text and original image anchors, read-only JSON snapshot
- `assets/images/`: all 358 extracted workbook embedded image files, including images reused in multiple positions

The export includes 17 source worksheets and 892 image placements (358 unique media files). Cell positions are kept as row and column labels. Images display alongside the worksheet row at which their Excel drawing anchor starts. Complex spreadsheet formatting, merged layouts, charts/shapes, external linked images and formulas are not replicated as an identical Excel pixel-perfect view; displayed values/text are a static export. Search is local. Update requires re-exporting data.

## Local preview

Run `python -m http.server 8000` in the extracted folder and open `http://localhost:8000`.

Style inspired by https://digikidult.github.io/Digimon-VER-WS/ . Unofficial, noncommercial fan website.
