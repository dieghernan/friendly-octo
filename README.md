# Oskar's Adventures

This blog is made with jekyll and uses the Chualapa theme (see below).

To make hosting as independent as possible, theme code is pulled into this repo.

Changes to the theme are made using vars in jekyll's `_config.yaml` and also in `assets/scss/main.scss`. Since the latter gives more convenient feedback in jekyll livereload most styling is done there rather than in `_config.yaml`.

scss variables that are overriden are mostly in `_sass/chulapa/variables.scss` and `_sass/bootstrap/variables.scss`.

## Chulapa Template 101

Click [**Use this template**](https://github.com/dieghernan/chulapa-101/generate) button above for cloning this repo and get started with [Chulapa Jekyll theme](https://github.com/dieghernan/chulapa).

Contains basic configuration to get you a site with:

- [Sample posts](./_posts/) and [paginated blog index](./blog/index.html).
- [Sample collection](./_cheatsheet/) with Markdown and kramdown cheatsheets and [collection index](./_pages/cheatsheet.md).
- Archive pages for posts grouped by year, category, and tag.
- Demo page with the different Bootstrap components and how they look with the actual skin settings.
- Sample 404 page.
- Site search with Lunr.
- Sample [`_config`](_config.yml) with minimal configuration.
- Sample [`algolia-search.yml`](algolia-search.yml) for using Algolia+GitHub Actions. More guidance in the top of the file.
- Sample files for extending the theme with your [own scripts](./_includes/custom/) and [css](./assets/css/).

[Configure as necessary](https://dieghernan.github.io/chulapa/docs/02-config) and replace sample content with your own.