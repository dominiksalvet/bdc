# Changelog

All notable changes to nconv will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and nconv adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

The changes not yet present in any release are listed in this section.

### Added

* Print a message when running in an interactive mode.

### Changed

* In default, interactive mode does automatic conversion for each number, not only for first.
* In interactive mode, each number may contain leading and trailing space/tab characters.

### Fixed

* Each number argument must be a single line argument.

## 1.0.0 (2020-10-28)

### Added

* When no number argument provided, nconv uses standard input.
* Added support for lowercase hexadecimal numbers on input.

### Fixed

* Fix extending functions when `bc` uses its result line breaks (`\<newline>`).

## 0.3.0 (2020-10-22)

### Added

* Added decimal conversions.
* Added hexadecimal conversions.
* Error messages contain also a unique ID. No reuse allowed.

### Changed

* Each result is printed as a single line.
* Internal number representation has been changed to respect `bc`.

## 0.2.0 (2020-10-17)

### Added

* The support for `help` and `about` has been added.
* Added constraining options for input (`bdhsu`) and output (`BDHW`).
* Added the first number analysis.
* Added binary conversions.

### Changed

* BDC has been renamed to nconv.

## 0.1.0 (2020-10-11)

### Added

* Make BDC GitPack-compatible (without any functionality so far).
