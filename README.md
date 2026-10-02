# object814.github.io

Personal academic homepage of Haoyu Zhou in a tech-brutalist style: exposed grid and hard 2px lines,
monospace type (JetBrains Mono) with Space Grotesk display, log- and table-style lists, one acid-lime accent.

## Editing content

All content lives in plain data files; the layout never needs touching for routine updates.

| What | File |
| --- | --- |
| Name, position, affiliation, contact links | `_config.yml` → `author` |
| About paragraph(s) | `_pages/about.md` |
| News | `_data/news.yml` (`highlight: true` marks a date in red) |
| Publications | `_data/publications.yml` (venue `kind`: `accepted`, `pending`, `oral`) |
| Projects | `_data/projects.yml` |
| Honours & awards | `_data/honors.yml` |
| Education | `_data/education.yml` |

Text fields accept Markdown links and **bold**. Quote any value that contains a colon or looks like a number
(e.g. `date: "2024.10"`), otherwise YAML will mangle it.

## Structure

- `_layouts/home.html` — the single-page template
- `assets/css/brutalist.css` — all styles (light/dark tokens, grid, records, tables)
- `images/` — portrait, publication figures, favicons

## Local preview

```bash
bundle install
bundle exec jekyll serve
```
