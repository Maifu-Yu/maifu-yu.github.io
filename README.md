# Maifu Yu — Personal Website

Personal website for Maifu Yu, built with the [Academic Pages](https://github.com/academicpages/academicpages.github.io) Jekyll template and hosted on GitHub Pages at [https://maifu-yu.github.io](https://maifu-yu.github.io).

## Sections

- **Home** (`/`) — short introduction, research interests, CV download, and Google Scholar link
- **Publications** (`/publications/`) — journal articles with links
- **Research** (`/research/`) — research experience and internships
- **CV** (`/cv/`) — full CV with a downloadable PDF (`files/CV-Maifu.pdf`)

## Run locally

Requires Ruby and Bundler:

```bash
bundle install
bundle exec jekyll serve -l -H localhost
```

Then open <http://localhost:4000>.

If `bundle install` hits permission errors, install gems locally first:

```bash
bundle config set --local path 'vendor/bundle'
bundle install
```

## Deploy

This repository is configured for GitHub Pages. Push to the `master` branch and the site builds automatically at `https://maifu-yu.github.io`.

## Updating content

- Site-wide settings (name, bio, links): `_config.yml`
- Home page: `_pages/about.md`
- Research page: `_pages/research.md`
- CV page: `_pages/cv.md`
- CV download: replace `files/CV-Maifu.pdf`
- Publications: edit files in `_publications/`
- Profile photo: replace `images/profile.png`
