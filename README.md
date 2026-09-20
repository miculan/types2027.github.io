# TYPES 2027

Website of **TYPES 2027**, the 33rd International Conference on Types for Proofs
and Programs, Udine, Italy, 7-11 June 2027.

Built with [Jekyll](https://jekyllrb.com/) and a custom theme; deployed to
GitHub Pages by the workflow in `.github/workflows/pages.yml`.

## Running the site locally

```sh
bundle install
bundle exec jekyll serve --livereload
```

The site is then at <http://localhost:4000>.

## Where things live

| Path | What it holds |
| --- | --- |
| `_config.yml` | Site settings and the conference facts used across the templates (`site.conference.*`) |
| `_data/dates.yml` | Important dates — the single source for every deadline table |
| `_data/navigation.yml` | The menu |
| `_data/committees.yml` | Committee members shown on the Organisation page |
| `_layouts/`, `_includes/` | The custom theme's templates |
| `assets/css/style.scss` | All the styling; the palette is the block of CSS variables at the top |
| `*.md` at the top level | One file per page |

## Editing content

- **A deadline changed.** Edit `_data/dates.yml`; every table on the site follows.
- **A page needs a new section.** Edit the corresponding `.md` file.
- **Committees are settled.** Fill in the `members` lists in
  `_data/committees.yml` (`name`, `affiliation`, optional `url` and `role`); the
  "to be announced" boxes disappear on their own.
- **Something is still unknown.** Mark it with
  `<span class="tba">to be announced</span>`, inside a
  `<div class="callout callout--tba">` when it deserves a box. Search the
  repository for `tba` to find everything still pending.

## Deployment

Pushing to `main` builds and deploys the site, provided that GitHub Pages is set
to build from GitHub Actions (Settings → Pages → Source: GitHub Actions).

The workflow passes the right `--baseurl` automatically. For local builds,
`_config.yml` assumes the site is served from the root of
`https://types2027.github.io`. If the repository stays under a personal account,
the published URL is `https://<user>.github.io/types2027.github.io/`; the
workflow handles that, but set `baseurl` in `_config.yml` if you need local
builds to match.
