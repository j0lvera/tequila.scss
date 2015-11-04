# Change Log
All notable changes to this project will be documented in this file.
This project adheres to [Semantic Versioning](http://semver.org/).

## [3.0.0] - 2015-11-04
### Changed
- Renamed to Tequila, because Bourbon and because I'm Mexican.

### Added
- `tequila-to` mixin for easy media queries management, with mobile first optional parameter.
- Start following [SemVer](http://semver.org) properly.

## 2.0.0 2014-11-05
### Changed
- Separate math logic from `cols()` mixin and create a new `core()` that does only that.

### Added
- Added better comments for documentation.
- Added `.fraction()` mixin to separate fractions logic from `.cols()`.
- Added `.namespace()` mixin to add `margin-left: 0;` to first element matching the attribute selector.

### Removed
- Removed `span()` mixin for grids without gutter.

## [1.0.3] - 2014-10-06
### Removed
- Removed mobile first code, not everyone uses it, and I don't want to force it.

## [1.0.2] - 2014-09-13
### Changed
- More descriptive comments.

## [1.0.1] - 2014-09-12
### Added
- `bower.json` file.

## 1.0.0 - 2015-11-04
### Added (Only the notable changes since public release)
- Ported from [hyx.less](https://github.com/thinkxl/hyx.less)
