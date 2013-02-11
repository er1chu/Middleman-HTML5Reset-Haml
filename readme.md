# Middleman 3.0.x Project Template: HTML5 RESET, HAML, Amazium, Sprockets Includes

An adaption of [HTML5 RESET](http://html5reset.org/) adapted as a HAML [Middleman 3.x](http://middlemanapp.com/) project template with [Amazium](http://amazium.co.uk) responsive grids ready to go, content using [Markdown](http://daringfireball.net/projects/markdown/), [SCSS](http://sass-lang.com/) organized with [SMACSS](http://smacss.com/), Coffeescript, Sprockets and more.

Middleman by [Danny Palmer](http://www.dannyprose.com)

Template thrown together by [Eric Hu](http://erichu.info)

Using [Bundler](http://gembundler.com/) and [RVM](https://rvm.io/) is **highly** recommended.

Features:

* Uses the [HTML5 Reset](http://www.html5reset.org), converted to a Middleman/HAML workflow.
* [Amazium](http://amazium.co.uk/) responsive grids ready to go.
* [SMACSS](http://smacss.com/) stylesheet organization
* [Middleman Livereload](https://github.com/middleman/middleman-livereload): enabled for the generic 'middleman' command by default
* Smart Site/Page handling for titles and descriptions (via the Middleman Docs source
* [Middleman Favicon Maker](https://github.com/follmann/middleman-favicon-maker): creates favicons and touch icons on build from `favicon_base.png` in /source/
* RVM-ready
* Some good `.gitignore` defaults

Hopefully this will save people some time. Add any suggestions to the [issue tracker](https://github.com/dannyprose/Middleman-HTML5-Boilerplate-HAML-Project-Template/issues).

## Usage

Download and install into ~/.middleman (you'll have to create this directory if it's not already there). You can then use it with the `--template` flag on `middleman init`. 

### Example

1. [Download](https://github.com/er1chu/Middleman-HTML5Reset-Haml/zipball/master)/clone to: `~/.middleman/haml-reset/`
2. Then create your new Middleman project: `middleman init my_new_project --template=haml-reset`

For more help follow [Middleman's project template instructions](http://middlemanapp.com/getting-started/welcome/).


## Documentation

Will come up with it as I go. For now [e-mail me](mailto:mail@erichu.info) with any questions or concerns.

## Older Middleman Versions

This will likely work with Middleman 2.x, but it's optimized for Middleman 3.x. You might have a few manual tasks to perform (e.g. bundling after `middleman init`, changing `Gemfile` version numbers, etc.). 

## Contribute

This was inspired by Danny's original [HTML5 Boilerplate-Haml build](https://github.com/dannyprose/Middleman-HTML5BP-HAML). If there are better defaults to include in a Middleman workflow, add them in. [I](http://erichu.info) just don't really like Boilerplate or Normalize or Susy.