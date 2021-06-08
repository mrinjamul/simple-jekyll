---
layout: page
title: Home
---

<img class="main_logo shadow" src="assets/apple-touch-icon-precomposed.png" alt="logo" />

Simple is simpliest jekyll theme.

- turn markdown to website
- Highly customizable

## Contents

- [Usage](#usage)
- [Development](#development)
- [Author](#author)
- [License](#license)

## Usage

### 1. Install dependencies

`Simple` is built on Jekyll and uses its built-in SCSS compiler to generate our CSS. Before getting started, you'll need to install the Jekyll gem and related dependencies:

```bash
bundle install
```

### Quick start

To help anyone with any level of familiarity with Jekyll quickly get started, `Simple` includes everything you need for a basic Jekyll site. To that end, just clone Simple and start up Jekyll.

```bash
git clone https://github.com/mrinjamul/simple-jekyll.git
```

### 3. Running locally

To see your Jekyll site with `Simple` applied, start a Jekyll server. In Terminal:

```bash
cd simple-jekyll
./tools/run
```

Open <http://localhost:4000> in your browser, and voilà.

### 4. Serving it up

If you host your code on GitHub, you can use [GitHub Pages](https://pages.github.com) to host your project.

1. Fork this repo and switch to the `gh-pages` branch.
1. If you're [using a custom domain name](https://help.github.com/articles/setting-up-a-custom-domain-with-github-pages), modify the `CNAME` file to point to your new domain.
1. If you're not using a custom domain name, **modify the `baseurl` in `_config.yml`** to point to your GitHub Pages URL. Example: for a repo at `github.com/username/simple`, use `http://username.github.io/simple/`. **Be sure to include the trailing slash.**
1. Done! Head to your GitHub Pages URL or custom domain.

No matter your production or hosting setup, be sure to verify the `baseurl` option file and `CNAME` settings. Not applying this correctly can mean broken styles on your site.

## Development

Simple has two branches, but only one is used for active development.

- `main` for development. **All pull requests should be to submitted against `master`.**
- `gh-pages` for our hosted site. **Please avoid using this branch.**

CSS is handled via Jeykll's built-in Sass compiler. Source Sass files are located in `_sass/`, included into `styles.scss`, and compile to `styles.css`.

## Author

- **Injamul Mohammad Mollah** <mrinjamul@gmail.com>

## License

Open sourced under the [MIT license](LICENSE).

## Want to contribute?

Learn more and contribute on [GitHub](https://github.com/mrinjamul/simple-jekyll).

Have questions or suggestions? Feel free to [email](mailto:mrinjamul@gmail.com) us.
