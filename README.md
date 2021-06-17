# hugo-drybones

scaffold for a hugo theme with nothing but semantic markup

run example site with: `make dev`, then visit `http://localhost:1313`.

## Use as starting point for your own Hugo theme

Clone [this repo](https://github.com/brendantang/hugo-drybones) or use it as a [template](https://github.com/brendantang/hugo-drybones/generate).

## Install as the theme for your site

~~~sh
cd /path/to/your/hugo/site
mkdir themes #if necessary
git submodule add https://github.com/brendantang/hugo-drybones themes/drybones
~~~

Add `theme = "drybones"` to `config.toml` 

