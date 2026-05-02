# Beichen Zhang Personal Website

Professional website for Beichen Zhang, built with Hugo and a customized Adritian-based theme.

## Project Structure

- `content/` page content, blog posts, CV, projects, and experience entries
- `config.toml` site configuration, menus, and theme settings
- `static/css/custom.css` custom design overrides
- `assets/images/` processed images used by the theme
- `layouts/` local template overrides for the Hugo theme
- `frontend/bootstrap/` vendored Bootstrap files required by the theme build

## Local Development

Build the site locally with:

```bash
hugo
```

Serve it locally with:

```bash
hugo server
```

## Deployment

The repository deploys through GitHub Actions using the workflow in `.github/workflows/hugo.yml`.

## Notes

- The site uses a small `i18n/` folder for theme text labels and metadata strings.
- Some theme partials are overridden locally in `layouts/` for compatibility with the current site setup.
