[comment]: <> "LTeX: language=en-GB"
<!-- markdownlint-disable MD003 MD025 MD033 -->

Loïc Grobol Personal Page
=========================

Repo to generate <https://loicgrobol.github.io>

Contact : [<loic.grobol@gmail.com>](mailto:loic.grobol@gmail.com)

## Build locally

```bash
rtx activate # ← adapt to your shell
gem install bundler
bundle config set --local path 'vendor/bundle'
bundle install
bundle exec jekyll build
bundle exec jekyll serve
```

## Notes

- Posts with the attribute `nav` set to true will be added to the nav bar, I recommend keeping them
  in [`_pages`](_pages).
- Chose the social profiles you want to display in [`data/settings.yaml`](data/settings.yaml) in the
  `social` mapping. The icons are pulled from font awesome.
- The style imports Bootstrap, so you can use everything it provides.
