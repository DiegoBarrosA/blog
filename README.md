
# My personal blog

## Integration and Shared Assets

This blog is part of a multi-site setup with:
- [Main site](https://diegobarrosaraya.com/)
- [Docs site](https://docs.diegobarrosaraya.com/)

All sites share a unified navigation bar and use a common CSS theme located in the `shared-assets/shared-theme.css` file at the root of the parent repository. This ensures consistent branding and easier updates across all sites.

## Deployment

Deployment is automated using GitHub Actions. On every push to `main`, the site is built with Jekyll and deployed to GitHub Pages. See `.github/workflows/deploy.yml` for details.

## Social Links

Contact and social links are managed via the Jekyll data file `_data/social.yml` for easy updates.

---
For more details, see the main site or docs site.
