# Changelog
All notable changes to this project will be documented in this file.

The format is based on
[Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to
[Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
### Changed
### Deprecated
### Removed
### Fixed
### Security



## [1.2.0] - 2022-06-29

### Changed
- Changelog moved from CHANGES to CHANGES.md and adapted to
  [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
- From now on version numbers adhere to
  [Semantic Versioning](http://semver.org/spec/v2.0.0.html)

### Fixed
- The 2022 June release of LaTeX breaks sanitize-umlaut (issue #1)
    A patch to `utf8.def` is added to circumvent `\protected` for
    two-octets UTF8 characters (including umlauts) inside `\index`



## [1.10] - 2020-01-01

### Added
- `utf8-2018` is a new supported encoding

### Changed
- implementation changed to adapt for LaTeX/inputenc UTF-8 changes
  (see documentation):
  version 1.00 is only compatible to older LaTeX/inputenc UTF-8
  version 1.10 is only compatible to recent LaTeX/inputenc UTF-8



## [1.00] - 2016-05-27

### Added
- Initial public release
