# About Feeds

Web feeds/RSS "getting started" guide for new users.

## Licenses

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License.](https://creativecommons.org/licenses/by-nc-sa/3.0/)

The icons under `icons/` are from [Wikimedia Commons](https://commons.wikimedia.org/wiki/File:Feed-icon.svg) and are used under the [Mozilla Public License Version 1.1](https://www.mozilla.org/MPL/1.1/).

## Development

Requirements: Ruby and Bundler should be installed. See GitHub's documentation [Testing your GitHub Pages site locally with Jekyll](https://docs.github.com/en/github/working-with-github-pages/testing-your-github-pages-site-locally-with-jekyll).

Clone this repo and enter the directory.

Install other requirements:

```bash
bundler install
```

Run the site locally:

```bash
bundle exec jekyll serve
```

Note that `Gemfile` specifies a version number for the `github-pages` gem. This should match the version given on the GitHub Pages [Dependency versions](https://pages.github.com/versions/) page. If this differs, update it and regenerate `Gemfile.lock`.

## Contributing

Contributions are welcome! Please see the [Issues](https://github.com/genmon/aboutfeeds/issues) for top-level concerns.
