# mikeogunmakin.github.io
A personal website where I share projects I’ve built, articles I’ve written, and ideas I’m exploring along the way.

Built with [Hugo](https://gohugo.io/) and the [PaperMod](https://github.com/adityatelange/hugo-PaperMod) theme.

## Development

```sh
git clone --recurse-submodules https://github.com/mikeogunmakin/mikeogunmakin.github.io.git
cd mikeogunmakin.github.io
hugo server -D
```

New articles go in `content/posts/`:

```sh
hugo new posts/my-article.md
```

## Deployment

Pushing to `main` triggers a GitHub Actions workflow ([.github/workflows/hugo.yml](.github/workflows/hugo.yml)) that builds the site with Hugo and deploys it to GitHub Pages.
