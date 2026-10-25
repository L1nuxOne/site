# l1nux.one

Public static site, deployed by GitHub Pages from `main` at the repository root.
The custom domain is retained in `CNAME`.

- `/`: existing L1nux.one landing page, with a link to Folderwing.
- `/folderwing/`: Folderwing homepage, using its existing coral/plum/cream branding.

To preview locally, run `python3 -m http.server 8765` in this directory and visit
`http://localhost:8765/folderwing/`.

The Folderwing page has no external fonts, scripts, analytics or build dependencies.
Its workspace and disk-usage graphics are labeled illustrations, not screenshots
or measurements. App facts and scope come from the public Folderwing repository.

For a future release, update the version, ZIP URL and download size in
`folderwing/index.html`, including the SoftwareApplication structured data.
Release notes, checksums, license notices, and source packages remain on GitHub.
