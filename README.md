# genieautocenter.com

The Genie Auto Center website, served by GitHub Pages at genieautocenter.com.

Don't edit these files by hand. The site is managed in Bolt Badger
(Settings → Website) and built by `tools/siteexport/export.mjs` in the
shop-desk repo.

`index.html` keeps itself current. The job in
`.github/workflows/snapshot.yml` runs every 15 minutes, rebuilds the page
from whatever the shop has published with the current page design, and
commits it when something changed. Between a publish and the next run,
visitors still see the new content: the page's script updates it in place.

To rebuild right away, run the "Rebuild the page from Bolt Badger" job by
hand from the Actions tab.
