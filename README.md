# link-dev.github.io

Personal academic homepage of **Junxiong Zhou** — [link-dev.github.io](https://link-dev.github.io/)

Built with [Jekyll](https://jekyllrb.com/) and a custom design. Originally based on
[luost26/academic-homepage](https://github.com/luost26/academic-homepage), later fully redesigned.

## Updating content

| What | Where |
| --- | --- |
| Profile, education, experience | `_data/profile.yml` |
| Publications | `_publications/<year>/<id>.md` (one file per paper) |
| News | `_news/<id>.md` |
| Showcase photos | `_data/gallery.yml` + images in `assets/images/photos/` |
| Navigation | `_data/navigation.yml` |
| Author display (bold / links) | `_data/authors.yml` |

Publication citation counts are fetched client-side from Semantic Scholar using the
`semantic_scholar_id` in each publication's front matter.

GitHub Pages builds the site automatically on push — no local build needed.
