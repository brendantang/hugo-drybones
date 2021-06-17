---
title: "Installing Drybones"
date: 2021-06-17T09:52:15-04:00
draft: false
---

You can install Drybones as the theme for your Hugo site by cloning it into the themes directory:

~~~
cd /path/to/your/hugo/site
mkdir themes #if necessary
git submodule add https://github.com/brendantang/hugo-drybones themes/drybones
~~~

And then adding `theme = "drybones"` to `config.toml`.

But it's more likely you want to just clone this repository and use it as a starting point for developing your own theme!
