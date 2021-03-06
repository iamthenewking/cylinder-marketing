# Cylinder Marketing Site

## About

This is the
marketing site for Cylinder,
found at http://cylinder.digital.

It's built in [Middleman].
We are deployed to [GitHub Pages].

[Middleman]: https://middlemanapp.com
[Github Pages]: https://pages.github.com



## About Middleman

Middleman is a static site generator built in Ruby. This makes it a great fit
for projects that may end up as a Ruby on Rails app. Its minimalistic structure
makes it very easy to work with, and includes support for deploying to Github
Pages.

## Includes

* [HAML](http://haml.info):
  Simple template markup
* [Sass (LibSass)](http://sass-lang.com):
  CSS with superpowers
* [Bourbon](http://bourbon.io):
  Sass mixin library
* [Neat](http://neat.bourbon.io):
  Semantic grid for Sass and Bourbon
* [Bitters](http://bitters.bourbon.io):
  Scaffold styles, variables and structure for Bourbon projects.
* [Middleman Live Reload](https://github.com/middleman/middleman-livereload):
  Reloads the page when files change
* [Middleman Deploy](https://github.com/karlfreeman/middleman-deploy):
  Deploy your Middleman build via rsync, ftp, sftp, or git (deploys to Github Pages by default)
* [Coffeescript](http://coffeescript.org):
  Write javascript with simpler syntax


## Getting Started

Clone up your project in your code directory.

### Ruby
Install a Ruby manager like

* [`rbenv`](https://github.com/rbenv/rbenv#basic-github-checkout) 
* [`chruby`](https://github.com/postmodern/chruby#install)
* [`rvm`](https://github.com/rvm/rvm#installation)

This repository uses the Ruby version specified in the
[.ruby-version](.ruby-version) file.

### Install dependencies
```
bundle install
```

### Run the server
```
bundle exec middleman
```

### Deploy to Github Pages

```
./bin/deploy
```


## Directories

Stylesheets, fonts, images, and JavaScript files
go in the `/source/assets/` directory.
Vendor stylesheets and JavaScripts
go in each of their `/vendor/` directories.

## Contributing

If you have problems, please create a
[GitHub Issue](https://github.com/adarsh/cylinder-marketing/issues).

Have a fix or want to add a feature?
[Pull Requests](https://github.com/adarsh/cylinder-marketing/pulls) are welcome!

## Credits


## License

Copyright © 2017 [Cylinder Digital, Inc.](http://cylinder.digital).
