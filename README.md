Window Maker webpage source
===========================

This is a web page source files. All of the files should be proper markdown
files accepted by [Jekyll](https://jekyllrb.com) static site generator.

Build/serve
-----------

In order to build the site, you'll need Jekyll framework installed and
[jekyll-rst](https://github.com/gryf/jekyll-rst) plugin. Easiest way
to achieve it, is to install it from system repositories.

If your distribution doesn't contain it (even in external ones, like PPA for
Ubuntu, AUR for Arch or some portage overlay from Gentoo), that it might be
installed locally using [Bundler](https://github.com/bundler/bundler).

Manual installation would be as follows:

```
$ git clone --recurse-submodules https://github.com/window-maker/window-maker.github.io
$ cd window-maker.github.io
$ bundler install
$ # install docutils and pygments from your distribution repository, or use
$ # following command to install them from PyPI for the current user:
$ pip install docutils pygments
```

To build and serve webpage in development mode, you just issue the following
command:

```
$ bundler exec jekyll serve
```

Consult [jekyll-rst](https://github.com/gryf/jekyll-rst) plugin documentation
for requirements. Other options for installing dependencies are also possible -
they might be installed from distribution repositories.

Last line will initialize gemfile, add jekyll to it, and then perform `jekyll
serve` which underneath will build the site and than run simple http server on
`http://localhost:4000` in development mode. More about jekyll you can find [on
it's page](https://jekyllrb.com/docs)
