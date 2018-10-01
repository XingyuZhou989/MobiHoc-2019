# MobiHoc 2019 Web Site

This repository contains code and data for the MobiHoc 2019 web site.

## License

Creative Commons Attribution-NonCommercial-ShareAlike 3.0 Unported License (see [LICENSE.md](LICENSE.md) for details).

#### Prerequisites

You will need `bower` tool.  On macOS with Homebrew

    sudo port install bower
    (or brew install bower)

On other system with nodejs installed:

    sudo npm install -g bower

You will need `xpdf` and `ImageMagick` to generate the conference program. On macOS with Homebrew

    brew install xpdf 
    brew install imagemagick
    sudo chown -R yourusername:admin /usr/local/include/
    brew link imagemagick
If you're not sure of your username, you can run the command

    whoami


#### Generating site using jekyll

The website uses jekyll engine to generate the website using the templates. To get started with jekyll, change to the source file directory and run

    sudo gem install jekyll bundler
    bundle install
    bower install
    bundle exec jekyll build

To generate the website and serve it from a local webserver, e.g., for debugging

    bundle exec jekyll serve

## Overview

The repository is organized as follows:

* `_config.yml` is a configuration file for the website, defining title, menu, and several basic parameters
* `_data/`      contains datasets in YaML or JSON format defining menu items, conference dates, news, and supporters
* `_includes/`  are supplementary scripts to generate website's content, including templates for menu, news, google analytics, and sponsors
* `_layouts/`   are layout files
* `_assets/`    CSS, javascript, and image assets
* `*.md`, `*.html` Individual pages in markdown or HTML format

## Getting started as MobiHoc web chair

You'll have to request an account at:

http://campus.acm.org/public/infodir/account_request.cfm

For questions or to check on status of your request, you may try following up with ishelpdesk@hq.acm.org. They may contact the general chairs for confirmation.

You should receive further instructions from ACM on how to upload content to the server when your account is setup.
