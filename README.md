# Islandora PDF.js

## Introduction

An Islandora viewer using [Mozilla PDF.js](http://mozilla.github.io/pdf.js/).

## Requirements

* [Islandora](https://github.com/discoverygarden/islandora)
* [Tuque](https://github.com/islandora/tuque)
* [PDF.js](http://mozilla.github.io/pdf.js/)

## Installation

Install as
[usual](https://www.drupal.org/docs/8/extending-drupal-8/installing-drupal-8-modules).

You also need to
[Download](http://mozilla.github.io/pdf.js/getting_started/#download) and
install the generic build of [PDF.js](http://mozilla.github.io/pdf.js) and
move the directory to sites/libraries/pdfjs folder, or run
`drush pdfjs-plugin`. 

Note: If you use the Drush command, ensure that your `.drush` directory contains
the install script `islandora_pdfjs.drush.inc`. If it doesn't, move (not copy)
the script from the `islandora_pdfjs` module's root directory to your `.drush`
folder before you run the drush command.

## Configuration

Currently the PDF.js viewer can be used as the viewer for:

* the [PDF Solution Pack](https://github.com/discoverygarden/islandora_pdf)
  * Configuration » Islandora » Solution pack configuration » PDF Solution Pack
    (admin/config/islandora/solution_pack_config/pdf).

## Documentation

Further documentation for this module is available at [our
wiki](https://wiki.duraspace.org/display/ISLANDORA/Islandora+PDF.js).

## Troubleshooting/Issues

Having problems or solved one? Create an issue, check out the Islandora Google
groups.

* [Users](https://groups.google.com/forum/?hl=en&fromgroups#!forum/islandora)
* [Devs](https://groups.google.com/forum/?hl=en&fromgroups#!forum/islandora-dev)

or contact [discoverygarden](http://support.discoverygarden.ca).

## Maintainers/Sponsors

Current maintainers:

* [discoverygarden](http://www.discoverygarden.ca)

## Development

If you would like to contribute to this module, please check out the helpful
[Documentation](https://github.com/Islandora/islandora/wiki#wiki-documentation-for-developers),
[Developers](http://islandora.ca/developers) section on Islandora.ca and create
an issue, pull request and or contact
[discoverygarden](http://support.discoverygarden.ca).

## License

[GPLv3](http://www.gnu.org/licenses/gpl-3.0.txt)

**Note** This module requires PDF.js. PDF.js is licensed under an [Apache2
License](https://github.com/mozilla/pdf.js/blob/master/LICENSE)
