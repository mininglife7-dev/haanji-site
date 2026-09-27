# haanji-site

Static HaanJi site published on GitHub Pages from the `gh-pages` branch.

Source of truth is `/workspace/receptionist-ai/site/` on the build box. The workflow `.github/workflows/sync.yml` mirrors every file in `files.txt` from the URL in `source_url.txt` (the box's current site tunnel) into `gh-pages`. To re-sync: update `source_url.txt` (or run the workflow manually).
