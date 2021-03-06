# Hugo Bootstrap v4 Blog
A simple [Hugo](https://gohugo.io) theme based on the [Bootstrap v4 blog example](http://v4-alpha.getbootstrap.com/examples/blog). Geared towards simple blogging. Still a work in progress.

![Screenshot](/screenshot@2x.png?raw=true "Screenshot")

## Features

- Basic [OpenGraph](http://ogp.me) and [Twitter Card](https://dev.twitter.com/cards/types) metadata support
- robots.txt linking to XML sitemap (disabled by default, see [Hugo docs](https://gohugo.io/extras/robots-txt/))

## Usage
Clone the repository to your site's `themes` directory. Refer to `exampleSite/config.toml` for optional configuration values.

## Building (For Developers)
This theme uses the [Bootstrap](https://getbootstrap.com/) framework. A static version of this is already included, but if you want to bump the version, tweak the style, etc, you'll need to rebuild the assets. Make sure you have NodeJS v4 or v6 installed, and then run the following from inside the theme's directory:

```
$ npm install
$ npm run build
```

## TODO

- tags + categories!
- add optional social links to sidebar
- add configurable license notice for footer
- add favicon
- add author page (for when you click author name in a post/summary)
- add images to sitemap? https://gohugo.io/templates/sitemap/

## License
This repository contains the code of [Bootstrap](http://getbootstrap.com), which is licensed under the [MIT license](https://tldrlegal.com/license/mit-license).

Otherwise, the contents are [GPLv3](https://www.gnu.org/licenses/gpl-3.0.txt).
