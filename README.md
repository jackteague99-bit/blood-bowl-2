# Blood Bowl 2.0

Static franchise-history website.

## Deploy

Upload `index.html` to a GitHub repository. In Cloudflare, create a Workers & Pages > Pages project and connect that GitHub repository. Choose no framework, no build command, and output directory `/` (repository root).

Historical data is embedded in `index.html`; updates require committing a new version. The site does not yet automatically sync Sleeper data.

## Privacy

This is a public website when deployed. Review historical manager names, scores and transactions before publishing.
