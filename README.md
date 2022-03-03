This repository contains the code for the Open Web Docs website.

It's currently built using [Hugo](https://gohugo.io/) with the [PaperMod](https://github.com/adityatelange/hugo-PaperMod/) theme.

## Running the site locally

Install Hugo 0.83.0 or higher.

Clone this repo, with the `--recursive` option, because PaperMod is a submodule:

```
git clone git@github.com:openwebdocs/website --recursive
```

Run:

```
hugo server
```

Visit the site at http://localhost:1313/ (or wherever Hugo tells you it is).

## Adding and editing content

Currently this site is 99% a blog. Blog posts live under /content/posts, and are written in Markdown with some YAML front matter.

## Deployment

Currently this site is deployed using Netlify when new commits are pushed to the "main" branch.
