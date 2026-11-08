# Lurking Ninja

This is the source for [lurking-ninja.com](https://lurking-ninja.com), a personal site about game development. It is built with Jekyll and hosted on GitHub Pages.

## Preview locally

Install Ruby and Bundler, then run:

```sh
bundle install
bundle exec jekyll serve
```

Open `http://localhost:4000` to view the site. The `github-pages` gem in the `Gemfile` keeps the local build aligned with GitHub Pages.

To create a production build without starting the preview server, run `bundle exec jekyll build`. The generated site is written to `_site`.
