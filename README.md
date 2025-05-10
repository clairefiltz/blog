# Claire's Blog

This is a personal blog built with [Hugo](https://gohugo.io/) and the [LoveIt](https://github.com/dillonzq/LoveIt) theme.

## Development

### Running locally

To start the local development server:

```bash
hugo server -D
```

This will run your site at http://localhost:1313/ with drafts enabled.

### Adding content

To create a new blog post:

```bash
hugo new content posts/my-new-post.md
```

To create other pages:

```bash
hugo new content page-name/index.md
```

### Structure

- `content/`: Where all your content lives
  - `posts/`: Blog posts
  - `about/`: About page
- `static/`: Static files like images
- `themes/`: Theme files
- `hugo.yaml`: Configuration file

## Deployment

### GitHub Pages

To deploy to GitHub Pages:

1. Create a repository named `clairefiltz.github.io`
2. Push this code to the repository
3. Set up GitHub Pages to deploy from your main branch

Alternatively, you can use GitHub Actions for more control over the build process.

## Customization

To customize the site:

1. Edit `hugo.yaml` to change site configurations
2. Add your avatar to `static/images/avatar.jpg`
3. Customize the theme according to the [LoveIt documentation](https://hugoloveit.com/documentation/) 