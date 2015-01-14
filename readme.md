Stardog Documentation
=====================

[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/clarkparsia/stardog-docs?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

We write Stardog docs in Asciidoc: Use rvm and bundler to setup a development environment
with two commands:

## Development Setup

* make an rvm environment; 2.1.5 works.  If you have rvm, `rvm use ruby 2.1.5`
* `cd src; bundle` for installing asciidoctor and related dependencies
* If one of the dependency fails, you can manually reinstall a gem with `gem install <gem>`, and then re-run `bundle`
* `cd src/style ; bundle install` to install the CSS processing
* Problems?  Run `rvm list` to see what version of Ruby you are using

## Editing Docs

* edit *.ad files using asciidoctor syntax
* edit SASS stuff in style if you need to tweak CSS (you probably don't)
* build with grunt

Be aware of [LICENSE.txt](http://creativecommons.org/licenses/by-sa/3.0/).
