# Tramdanglamduoc.github.io

Personal website of Trần Ngọc Bảo Trâm, built with Jekyll and served by GitHub Pages.

## Editing content

Most content lives in `_data/`, so updates rarely need HTML:

| File | What it holds |
|---|---|
| `_data/stations.yml` | Lab platforms on the homepage and the navbar tabs (same list, same order) |
| `_data/now.yml` | "Now" section on the homepage |
| `_data/news.yml` | Recent news, newest first (homepage shows five) |
| `_data/projects.yml` | Project cards: problem → method → result |
| `_data/publications.yml` | Selected and earlier publications |
| `_data/repos.yml` | Open Science page |

Pages: `index.html`, `about.html` (journey map), `projects.html`, `publications.html`, `talks.html`, `open-science.html`, `contact.html`.

Set `booking_url` and `cv` in `_config.yml` when they're ready.

## Run locally

```bash
gem install jekyll
jekyll serve
```

## Credits

- Lab illustrations: macrovector on Freepik
- Map data: Natural Earth via world-atlas
- The idea of navigating a site through one illustrated scene comes from Cecilia Baldoni's website
