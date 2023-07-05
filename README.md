# Open mSupply Documentation

This repo contains the public documentation for Conforma, hosted on [https://docs.conforma.nz](https://docs.conforma.nz/docs/introduction/).
Documentation is stored in markdown files and built using [zola](https://www.getzola.org/documentation/getting-started/installation/)

## Getting Started

To edit the docs, first clone this repo locally. Then install zola: https://www.getzola.org/documentation/getting-started/installation/

You should be able to run the docs locally now, by opening a terminal or command prompt, navigating to the directory you've cloned into and entering

```
zola serve
```

The docs will then be available to view locally on http://localhost:1111

If you encounter an error:

```
Error: Failed to render section '/msupply_docs/content/_index.md'
Reason: Failed to render 'index.html': error while rendering macro `macros_header::header` (error happened in a parent template)
Reason: Variable `config.default_language` not found in context while rendering 'macros/header.html'
```

ensure that you are running a recent version of zola.
`zola 17.2` is known to work but there is a problem with `v0.14.0`, to check your version with run `zola --version` from terminal or a command prompt.

## Contributing

Create a branch and create a pull request for review. 

If you wish to serve images from a subdirectory rather than co-locating the content or storing in the static folder, you have to include an index file (`_index.md`) for the subdirectory to be included in the build.

## Deployment

This repo is automatically deployed to github pages on push to main. The github action is defined in `.github/workflows/static_deploy.yml`

The deployment code uses `shalzz/zola-deploy-action@master`
