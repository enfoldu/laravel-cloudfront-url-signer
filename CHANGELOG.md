# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).


## [Unreleased]

## [2.2.0] - 2019-08-10
### Added
- Added support and instructions for Lumen 5.8

## [2.1.0] - 2019-06-03
### Added
- Added support for L5.8

## [2.0.0] - 2018-09-24
### Added
- Added support for L5.7

### Removed
- Removed support for L5.5

## [1.0.1] - 2018-04-22
### Added
- Updated CHANGELOG to cover undocumented releases

### Changed
- Removed dependency and consequentially php-intl extension: it gives some problems on High Sierra development environment. URL check is now delegated to AWS SDK. 

## [1.0.0] - 2018-02-19
### Added
- Add support for L5.6

## [0.1.5] - 2018-02-18
### Fixed
- getExpirationTimestamp now returns int value instead of string to overcome an AWS SDK bug

## [0.1.4] - 2018-02-13
### Changed
- Refactored tests
- Switched to UrlSigner class instead of CloudFrontClient

## [0.1.3] - 2018-02-09
### Changed
- $expiration default behaviour moved to internal `sign()` method instead of helper

## [0.1.2] - 2018-02-09
### Fixed
- Fixed config publishing

### Changed
- $expiration parameter of `sign()` helper now defaults to the value defined in the configuration file when not defined

## [0.1.1] - 2018-02-09
### Added
- Added `sign()` helper

## [0.1.0 - 2018-02-09
- Initial release
