# Doxter Changelog
> Markdown Editor & Parser for [Craft CMS](http://craftcms.com)

## Doxter 3.1.0 - 2017.16.04
### [Added]
- Added emoji support as requested on issue #5 👍 
- Added (back) support for reference tag parsing
- Added full documentation as a Wiki

### [Fixed]
- Fixed full viewport editing while in the Doxter field
- Fixed issue #4 where `entry.doxterField` would render escaped html

### [Updated]
- Updated codebase to adhere to Craft Coding Standards

## Doxter 3.0.8 - 2017.11.04
### [Fixed]
- Fixed full viewport editing from issue #2

### [Updated]
- Updated plugin.(css|js) to use spaces
- Updated plugin.js to include semi-colons where missing

## Doxter 3.0.7 - 2017.02.04
### [Fixed]
- Fixed issue where `hasSettings` is no longer supported

### [Updated]
- Updated all dependencies to the latest stable version

## [3.0.6] - 2017.06.02
### [Fixed]
- Fixed critical issue where the Shortcode parser would pee himself if fields were empty

## [3.0.5] - 2017.06.02
### [Added]
- Added SmartyPants as a dependency for handling typography
- Added back support for **Shortcodes**
- Added back the `doxter()` global to access the public API
- Added a new `DoxterEvent` to notify about parsing events
- Updates plugin icons

## [3.0.4] - 2017.03.01
### Added
- Added prettier icons

### Updated
- Updated the way components are accessed for improved type hinting

### Fixed
- Fixed an issue where the variable class was loaded

## [3.0.3] - 2017.02.01
### Added
- Added cover image and updated icons

## [3.0.1] - 2017.02.01
### Added
- Added changelog and documentation URLs

### Fixed
- Fixed an issue where parsers were not instantiated correctly

## [3.0.0] - 2017.02.01
- Initial (beta) release for Craft 3
