# kulbir.github.io

Personal portfolio and tools landing page.

## Live Site

🔗 **https://kulbir.github.io/**

## Tools

| Tool | URL | Description |
|------|-----|-------------|
| AlgoWalkthrough | [/AlgoWalkthrough/](https://kulbir.github.io/AlgoWalkthrough/) | Interactive LeetCode algorithm visualizer |

## Deploy

This repo auto-deploys to GitHub Pages when you push to `main`.

## Adding New Tools

1. Create a new repo for your tool
2. Set up GitHub Pages with Actions
3. Add a card to `index.html`:

```html
<a href="/YourToolName/" class="tool-card">
  <div class="tool-header">
    <span class="tool-icon">🔧</span>
    <span class="tool-title">Your Tool Name</span>
    <span class="tool-badge">Live</span>
  </div>
  <p class="tool-description">
    Description of your tool.
  </p>
  <div class="tool-tags">
    <span class="tag">Tag1</span>
    <span class="tag">Tag2</span>
  </div>
</a>
```

