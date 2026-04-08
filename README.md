# GitHub Repo Card

A lightweight Web Component that renders a GitHub repository card with:

- stars, forks, contributors, and open issues
- localStorage caching to soften GitHub API rate limits
- latest release badge

## Demo

Try the live demo on GitHub Pages:

[https://illeatmyhat.github.io/github-repo-card/](https://illeatmyhat.github.io/github-repo-card/)

You can also open `index.html` locally.

## Usage

```html
<script src="./github-repo-card.js"></script>

<github-repo-card repo="agenttoolkit/altk-evolve"></github-repo-card>
<github-repo-card repo="torvalds/linux" compact></github-repo-card>
```

### Attributes

- `repo`: repository in `owner/name` format
- `cache-ttl`: cache TTL in seconds, defaults to `10800`
- `compact`: hides the description, size, and refresh button
