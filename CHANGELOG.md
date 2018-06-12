# Changelog

## [2.0.0] - 2018-06-12
### Changed
- SS 4 support.

## [1.1.2] - 2016-02-17
### Fixed
- Updated the `$time_limit` variable to be overridden via the YML config.

## [1.1.1] - 2015-12-17
### Added
- Updated module to work with SilverStripe 3.2.
- Included `.editorconfig` file.

## [1.1.0] - 2015-09-28
### Added
- Included changelog.
- Included `.gitattributes` file.
- Included `php` version `>=5.3.0` as a dependency.
- Included `scrutinizer/ocular` version `~1.1` as a development dependency.
- Updated license.
- Update Scrutinizer configuration.
- Update Travis configuration (include PHP 5.6, 7 and HHVM).
- Update PHPUnit configuration.
- Include contributing guide.
- Update readme.
- Included test case for failed validation.

### Fixed
- Removed `composer.lock` file.
- Updated `.gitignore` file.
- Updated `composer.json` file.
- Improved PSR-1 and PSR-2 conformance.
- Included safe mocking of translation function.
- Corrected `getValidator()` to return `MockInterface`.

## [1.0.1] - 2014-09-09
### Added
- Included `silverstripe/spamprotection` version `~1.2.0` as a dependency.

### Changed
- Excluded methods from code coverage calculations.

[1.1.1]: https://github.com/symbiote-library/silverstripe-spamprotection-honeypot/compare/1.1.0...1.1.1
[1.1.0]: https://github.com/symbiote-library/silverstripe-spamprotection-honeypot/compare/1.0.1...1.1.0
[1.0.1]: https://github.com/symbiote-library/silverstripe-spamprotection-honeypot/compare/1.0.0...1.0.1