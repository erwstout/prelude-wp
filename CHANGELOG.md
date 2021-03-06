# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [3.4.1] - 2016-12-19
# Update
- Updates npm dependencies 

## [3.4.0] - 2016-12-16
# Update
- Updates default gulp task to run `styles` instead of `sass`
- Moves all theme files out of `/src/` and into the root folder

## [3.3.11] - 2016-12-01
# Removes
- Removes hiding of post author div

## [3.3.11] - 2016-11-21
### Fixes and Additions
- Fixes missing dependency `imagemin-pngquant`
- Fixes missing default argument for `featuredURL()`
- Adds `THEME_VERSION` constant to better enqueue JS and CSS files (avoiding cache issues)

## [3.3.10] - 2016-10-13
### Added
- Adds function to expand WordPress toolkit/kitchen sink for all users by default.

## [3.3.9] - 2016-10-11
### Removed
- Removes the `postinstall` script all together to avoid changes to user themes and also greatly increase compatibility across platforms. Also updates readme with this change.

## [3.3.8] - 2016-10-05
### Change
- Changes the WordPress jQuery handle from `prelude_wp` to `jquery` for better plugin compatibility.

## [3.3.7] - 2016-09-21
### Update
- Adds SVG as a supported file time for image compression.

## [3.3.6] - 2016-09-15
### Update
- Updates package gulp task to compile correctly and ignore `node_modules` & `bower_components` / Issue #77

## [3.3.5] - 2016-09-13
### Update
- Updates cssnano optimizations in `gulpfile.js`

## [3.3.4] - 2016-08-31
### Change
- Updates autoprefixer browser support / Issue #75

## [3.3.3] - 2016-08-18
### Added
- Hides empty paragraphs with p:empty style from @bebaps / Issue #74

## [3.3.2] - 2015-12-03
### Added
- Change log
- Touch detection based on Gist from @billerickson
