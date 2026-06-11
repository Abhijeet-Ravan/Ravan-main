# Generated static pages

The `output/` folder contains the standalone HTML files requested for the Zoom-required public routes.

## Route map

index.html      -> /
privacy.html    -> /privacy
terms.html      -> /terms
support.html    -> /support
docs-zoom.html  -> /docs/zoom

## What changed in `index.html`

- Copied the existing homepage into `output/index.html`.
- Added footer links for `/privacy`, `/terms`, `/support`, and `/docs/zoom`.
- Left the existing homepage sections, scripts, animations, and product content intact.

## Notes

- Deployment is not included in this task.
- The legal, support, and Zoom docs pages are standalone lightweight HTML files and do not load the homepage's heavy dependencies.
