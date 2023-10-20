# polymathic

> The theme is in active development

polymathic is a [Zola](https://www.getzola.org/) portfolio theme. 

I made it for my own portfolio. The theme is called `polymathic`, inspired by individuals with a wide range of talents. The theme focuses on rich and consistent navigation experience, exposing the variety of topics to chose from, yet allowing the user to focus on a single thread of your story once they've made a choice. 

Docs and theme demo are available here [main--polymathic-demo.netlify.app](https://main--polymathic-demo.netlify.app/) 

This theme uses [Bulma](https://bulma.io/) scss framework, making the theme styles highly customizable and enabling mobile first theme design.

This theme uses [Animate.css](https://animate.style) for animations.

This theme adds minimal [Open Graph](https://ogp.me/) tags to every page `head`.

You can quickly deploy the theme to [netlify](https://docs.netlify.com/site-deploys/create-deploys/), theme comes with a config file.

## Features

See all features [demonstrated in the docs](https://main--polymathic-demo.netlify.app/features). 

### Media support

The theme is friendly to wide range of screen sizes from `mobile` to `fullhd`. Theme comes with minimal styles for `print` media.

### Navigation

This theme builds navigation for your site. The outcome is highly customizable via your `config.toml` and front-matter of your sections.

### Templates

The theme comes with templates for `index.html`, `page.html`, `section.html`, `taxonomy_list.html`, `taxonomy_single.html`, `404.html`. You can use them in your Zola project as is or by extending them, templates are divided in `block`s and `partials/*.html` for convenience of extending the theme.

### Brand and style

The theme is highly customizable via `config.toml` and sass variables. Your customization can start from just the primary color or extend all the way to bulma variables.


### Shortcodes

The theme comes with several shortcodes for building forms, galleries, navigation cards and banners.

## Install

Once you already have zola installed and ran `zola init`, then run from your project directory

    $ git init
    $ git submodule add https://github.com/anvlkv/polymathic themes/polymathic

You will also need [npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) installed, then run

    $ npm --prefix themes/polymathic install

For those using netlify deployments config is available here

    $ cp themes/polymathic/netlify.toml netlify.toml

In your `config.toml` Set zola theme to polymathic

    theme = "polymathic"


## Contributing

Issues or contributions are welcome. Also, curious what you make with it.

