# Download (field)

Provides a field type to build file downloads as single zipped file, collected
from multiple file fields.
Content authors can decide per entity, from which fields the zip file gets
collected, and what the link text should be.

Admins can decide, how the file name of that zip file is constructed using
tokens.

## Requirements

- The PHP zip extension has to be available (also required by the Installer
  core module)

## Installation

- Install this module using the official 
  [Backdrop CMS instructions](https://docs.backdropcms.org/documentation/extend-with-modules)
- Grant the "See download link" permission to appropriate roles.
- Attach "Download all files" field(s) to the content types you need
  combined zip downloads for.

## Issues

Bugs and Feature requests should be reported in the
[Issue Queue](https://github.com/backdrop-contrib/download/issues)

## Current Maintainers

- [Indigoxela](https://github.com/indigoxela)
- Seeking additional maintainers

## Credits

Created for Drupal by [Pierco](https://www.drupal.org/u/pierco).

## License

This project is GPL v2 software. See the LICENSE.txt file in this directory for complete text.
