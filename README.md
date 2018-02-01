# IMDB Redesign

This is redesign of the IMDB home page that uses HTML and CSS only, links have hover states but do not lead anywhere.

## ITCSS and BEM

This project uses [ITCSS structure](https://github.com/8thlight/design-styleguide#scss) and [BEM Naming Convention](https://csswizardry.com/2013/01/mindbemding-getting-your-head-round-bem-syntax/) for clean, modular code in compliance with [8th Light Style Guide](https://github.com/8thlight/design-styleguide)

## Jekyll Requirements

This project runs on Jekyll. Before you start, make sure your system has the following:

- GNU/ Linux, Unix, or macOS
- Ruby v2.2.5 or above (run > `ruby -v` to check your installation)
- RubyGems (run > `gem -v` to check)</li>
- GCC and Make (run > `gcc -v`, `g++ -v` and `make -v`to check)

## Install Jekyll with RubyGems

> `gem install jekyll`

## Starting the Server

> `jekyll serve`

By default, the server will run at `http://localhost:4000`.

## Known Issues

Next steps will includes fixes for:

- wrap all clickable areas with an `<a>` tag instead of `<div>` to demonstrate semantic markup and give code more meaning
- `c-button__icon-text` doesn't wrap correctly at smallest medium size
- give all clickable areas (images) a more graceful hover transition
