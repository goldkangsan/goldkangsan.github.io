# Kangsan Keum's website

Source for Kangsan Keum's personal website, based on the [al-folio](https://github.com/alshedivat/al-folio) Jekyll theme.

The repository still contains example pages and content from the theme. Review those files before treating the site as a complete profile.

## Where to edit

- `_config.yml`: site name, URL, navigation, and feature settings.
- `_pages/about.md`: home page introduction.
- `_pages/`: other pages, including projects, publications, and CV.
- `_data/`, `_bibliography/`, and `_posts/`: structured content, publications, and posts.
- `.github/workflows/jekyll.yml`: GitHub Pages build and deployment workflow.

## Local preview

Use a Ruby environment compatible with the `Gemfile`, then run:

```bash
bundle install
bundle exec jekyll serve
```

Open the local URL printed by Jekyll. See the upstream [installation guide](https://github.com/alshedivat/al-folio/blob/main/INSTALL.md) for theme dependencies and troubleshooting.

## Publishing

The workflow deploys pushes to `main` using GitHub Actions. In the repository's **Settings → Pages**, select **GitHub Actions** as the build and deployment source. Check the latest workflow run and the public URL after deployment; a workflow file alone does not establish a working site.

## Credits and license

The site uses [al-folio](https://github.com/alshedivat/al-folio). See [LICENSE](LICENSE) and the upstream project for licensing and theme documentation.
