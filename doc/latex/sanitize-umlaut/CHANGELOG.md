# Changelog
All notable changes to this project will be documented in this file.

The format is based on
[Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to
[Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added
### Changed
### Deprecated
### Removed
### Fixed
### Security



## [1.4.0] - 2026-02-10

### Added
- Description of nearly drop-in replacement of `makeindex` and `sanitize-umlaut`
    by `upmendex`

### Changed
- `CHANGES.md` renamed to `CHANGELOG.md` following https://keepachangelog.com/en/1.1.0/
- `\AtBeginDocument` replaced by `\AddToHook{begindocument}`
- `inputenc` references removed

### Fixed
- Documentation produced with `minted2` instead of `minted` (currently not compatible to Python>=3.14)



## [1.3.0] - 2023-05-15

### Added
- Support for lualatex and xelatex

### Changed
- The style file `sanitize-umlaut.sty` is UTF-8 encoded now and contains umlauts



## [1.2.1] - 2022-06-29

### Fixed
- The implementation of 1.2.0 changed UTF8 characters globally, not locally
    inside `\index`. The fix works locally as intended and only affects
    characters with UTF8-encoding C3..



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
