# Changelog

All notable changes to this project are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/2.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Changed

- The readme contribution, issue, and usage links open the Roots & Fruit repository. The Twitter reply is @learnwithmattc.

### Removed

- The donate link.

## [1.3.2] - 2026-10-21

### Changed

- **Breaking:** Reorder by Term now requires Reorder Posts, and WordPress 6.5 or newer. WordPress will not activate it on its own. An already active copy is deactivated on the next admin load when Reorder Posts is inactive.

### Fixed

- A post that loses a term no longer keeps that term's reorder field. It drops out of the Reorder by Term list, and out of a query for that field, when the post is saved or its terms change.

## [1.3.1] - 2026-03-23

- Fixed order reset issue when saving posts.

## [1.3.0] - 2025-02-15

- Fixing "term builder" where building terms often resulted in a mismatch, preventing reordering.
- Resolving PHP fatal error when loading the plugin.

## [1.2.3] - 2019-02-16

- Updating terms query in the back-end for better usability

## [1.2.2] - 2016-08-14

- Major CSS overhaul

## [1.2.0] - 2016-08-12

- Added screen options to set posts per page

## [1.1.0] - 2016-08-08

- Added option in `Settings->Reorder Posts` to disable the term query from displaying.
- Added better support for the post object.

## [1.0.0] - 2015-01-27

- Updated 2015-04-25 - Ensuring WordPress 4.2 compatibility
- Initial Release. Feedback is much appreciated!

[Unreleased]: https://github.com/Roots-and-Fruit/reorder-by-term/compare/1.3.2...HEAD
[1.3.2]: https://github.com/Roots-and-Fruit/reorder-by-term/compare/1.3.1...1.3.2
[1.3.1]: https://github.com/Roots-and-Fruit/reorder-by-term/compare/1.2.2...1.3.1
[1.2.2]: https://github.com/Roots-and-Fruit/reorder-by-term/compare/1.2.0...1.2.2
[1.2.0]: https://github.com/Roots-and-Fruit/reorder-by-term/compare/1.1.0...1.2.0
[1.1.0]: https://github.com/Roots-and-Fruit/reorder-by-term/compare/1.0.0...1.1.0
[1.0.0]: https://github.com/Roots-and-Fruit/reorder-by-term/releases/tag/1.0.0
