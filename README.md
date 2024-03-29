# Projects site

Website to inform about the projects done by the Foundation for Public Code.

This site builds with [Jekyll](http://jekyllrb.com/), as is the default of [GitHub pages](https://pages.github.com/) and uses the [Foundation for Public Code Jekyll Theme](https://github.com/publiccodenet/jekyll-theme).

[![pages-build-deployment](https://github.com/publiccodenet/projects/actions/workflows/pages/pages-build-deployment/badge.svg)](https://github.com/publiccodenet/projects/actions/workflows/pages/pages-build-deployment)
[![Test](https://github.com/publiccodenet/projects/actions/workflows/test.yml/badge.svg)](https://github.com/publiccodenet/projects/actions/workflows/test.yml)
[![Scheduled link check](https://github.com/publiccodenet/projects/actions/workflows/link-check.yml/badge.svg)](https://github.com/publiccodenet/projects/actions/workflows/link-check.yml)

## Installing locally

1. To build the site locally make sure you have [Ruby](https://www.ruby-lang.org/en/) and [Bundlr](https://bundler.io/) installed.
2. Install the dependencies of this repo with

```bash
$ bundle install
```

## Serving Locally

1. Run the Jekyll server with

```bash
$ bundle exec jekyll serve
```

2. You can now view the website locally on `http://localhost:4000`

The server will rebuild the site every time a file changes, with the exception of `_config.yml`.

## License

© 2018 Foundation for Public Code
