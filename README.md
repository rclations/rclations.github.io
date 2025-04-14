# RC Lachance's Personal Website

This is a personal website built with [Hugo](https://gohugo.io/) and the [Winston theme](https://themes.gohugo.io/themes/hugo-winston-theme/).

## Development

To run the site locally:

```bash
hugo server -D
```

This will start a local development server at http://localhost:1313/

## Deployment

This site is automatically deployed to GitHub Pages using GitHub Actions. Any changes pushed to the `main` branch will trigger a new build and deployment.

The live site is available at: https://rclations.github.io/

## Content Management

- Blog posts are stored in the `content/posts/` directory
- Pages are stored in the `content/` directory
- Site configuration is in `hugo.toml`
- Author information is in `data/author.json`
