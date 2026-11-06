# nathanbeam.dev

Personal site built with [Hugo](https://gohugo.io) and a small custom theme. GitHub
Actions builds and deploys it to GitHub Pages on every push to `main`.

## Local development

```sh
brew install hugo
hugo server -D        # http://localhost:1313, includes drafts
```

## Where things live

| Edit this | To change |
|-----------|-----------|
| `content/_index.md` | Home page headline, intro, pillars, metrics, selected work |
| `data/experience.yaml` | Experience page roles, skills, education, community |
| `hugo.toml` | Site title, description, links, nav |
| `assets/css/main.css` | Styles and color tokens (light and dark) |
| `layouts/` | Templates |

## Write a post

```sh
hugo new content writing/my-post-slug.md
```

Posts start as drafts. Set `draft: false` to publish. Fill in `description`; it
drives the post list, search snippets, and social previews.
