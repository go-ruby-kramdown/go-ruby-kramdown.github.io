<p align="center"><img src="https://raw.githubusercontent.com/go-ruby-kramdown/brand/main/social/go-ruby-kramdown.png" alt="go-ruby-kramdown/go-ruby-kramdown.github.io" width="720"></p>

# go-ruby-kramdown.github.io

The organization's institutional landing page, served at
<https://go-ruby-kramdown.github.io> and built with [Hugo](https://gohugo.io). It is a
single page (custom `layouts/index.html`).

Documentation lives in a separate repository,
[go-ruby-kramdown/docs](https://github.com/go-ruby-kramdown/docs), served at
<https://go-ruby-kramdown.github.io/docs/>. This page links there.

`.github/workflows/deploy-pages.yml` builds the landing with Hugo and deploys it
to GitHub Pages on every push to `main`.

## Local preview

```bash
hugo server      # http://localhost:1313
```
