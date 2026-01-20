# Funka We4Authors mirror (2026-01-20)

This folder contains a polite `wget` mirror of the We4Authors section on funka.com captured on 2026-01-20.

## Scope
- Start page: https://www.funka.com/en/projekt/we4authors/
- Objectives: https://www.funka.com/en/projekt/we4authors/what-is-we4authors/we4authors-main-objectives/
- Main activities and results: https://www.funka.com/en/projekt/we4authors/we4authors-main-activities-and-results/
- Market analysis: https://www.funka.com/en/projekt/we4authors/we4authors-main-activities-and-results/market-analysis-and-benchmarking-process-of-existing-cms/
- Workshops on accessible CMS: https://www.funka.com/en/projekt/we4authors/we4authors-main-activities-and-results/workshops-on-accessible-content-management-systems/
- Accessibility guidelines: https://www.funka.com/en/projekt/we4authors/we4authors-main-activities-and-results/accessibility-guidelines-for-the-cms-community-suppliers-and-public-governments/
- (Discovered via crawl) Partnership, dissemination, collaboration/testing, and workshop subpages under the same subtree.

## Command
```
wget --mirror --page-requisites --convert-links --adjust-extension --no-parent \
  --domains=www.funka.com --wait=1 --random-wait \
  --directory-prefix=archive/funka.com_20260120 \
  --input-file=archive/funka-we4authors-urls.txt
```

## Known issues
- `wget` exited with code 8 due to repeated 404s on unrelated start images (e.g., `/globalassets/projekt/*/startsida/startimage_live.jpg` and `/globalassets/startsida/siteBgImage_start.jpg`). The primary We4Authors pages and assets saved correctly.
- If a specific image or asset is missing, check the Wayback Machine for the closest snapshot and drop recovered files into the matching path under this folder; note any additions here.

## Notes
- Links are converted for offline browsing. Open `www.funka.com/en/projekt/we4authors/index.html` from this directory to navigate.
- Respect Funka’s terms of use if redistributing beyond local archival.
