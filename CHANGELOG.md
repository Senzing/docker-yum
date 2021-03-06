# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
[markdownlint](https://dlaa.me/markdownlint/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.1.4] - 2021-02-12

### Changed in 1.1.4

- Make Senzing YUM repository URL a docker build argument. (`SENZING_YUM_REPOSITORY_URL`)

## [1.1.3] - 2020-01-27

### Deleted in 1.1.3

- Specific mention of `senzingdata-v1` is deleted.
  It is automatically installed via `senzingapi` dependency.

## [1.1.2] - 2019-11-13

### Changed in 1.1.2

- Added support for MSSQL.

## [1.1.1] - 2019-10-24

### Added in 1.1.1

- Fix package name to senzingdata-v1

## [1.1.0] - 2019-09-01

### Added in 1.1.0

- Now installs 2 packages (senzingdata, senzingapi)

## [1.0.0] - 2019-08-05

### Added in 1.0.0

- Basic wrapper over **yum**
