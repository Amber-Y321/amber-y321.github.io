# Portfolio MVP replacement package

This folder contains replacement files for the existing GitHub Pages repository.

## Replace existing files

- `index.md`
- `_config.yml`
- `_data/navigation.yml`
- `about.md`
- `assets/css/custom.css`
- `_includes/head/custom.html`

## Add one new file

- `projects/ecommerce-command-center.md`

Existing files in `materials/` remain unchanged. The current `GIF_Dashboard.gif`, profile photo, and resume paths are reused.

`_includes/head/custom.html` loads the portfolio stylesheet through the Minimal Mistakes theme. The former `defaults.css` setting in `_config.yml` was removed because the theme does not render it as a stylesheet link.

## Before publishing

1. Confirm the resume filename is still `Resume of Yahan_2025.pdf`.
2. Add a LinkedIn link to `_config.yml` when available.
3. Replace the dashboard GIF with a current hero screenshot when the four-page dashboard exports are ready.
4. Validate the `+43.1%` and `+49%` wording against the final measurement period.
