# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.1.0] - 2020-03-06

### Added

- Separate README.md for the base image.

### Changed

- Switched to Ubuntu 18.04 LTS for the base image.
- New fhooe/fhooe-webdev box built upon the base image.
- Update to PHP 7.4.
- Update to MariaDB 10.4.
- Update to Redis Server 5.0.
- Update to Elasticsearch 7.6.
- Update to latest Composer, PHP_CodeSniffer and phpMyAdmin versions.
- README.md updated with current instructions.
- Elasticsearch service is stopped upon startup to save memory. 

## [1.0.0] - 2018-04-30

### Added

- Initial release of this Vagrantfile. Uses the fhooe/fhooe-webdev box.
- Initial release of the fhooe-webdev-base Vagrantfile that enhances a ubuntu/bento-16.04 box with Apache2, PHP 7.1, Redis Server and Elasticsearch.
- Various shell scripts for convenience.
- phpinfo.php for easy installation checks.

[Unreleased]: https://github.com/Digital-Media/fhooe-webdev/compare/v1.1.0...HEAD
[1.1.0]: https://github.com/Digital-Media/fhooe-webdev/compare/v1.0.0...v1.1.0
[1.0.0]: https://github.com/Digital-Media/fhooe-webdev/releases/tag/v1.0.0
