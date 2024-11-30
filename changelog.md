# Changelog

All notable changes to nconv will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and nconv adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

The changes not yet present in any release are listed in this section.

### Added

* Print hints to use `nconv help` when it might be needed.

### Fixed

* Entering a negative decimal number with two or more digits now work under Bash shells.

## 1.1.0 (2021-02-11)

### Added

* Print a message when running in an interactive mode.
* Add support for `0x` and `0X` prefixes in input hexadecimal numbers.
* Added option `-x` to enable showing more conversion details.

### Changed

* Adapt to new GitPack 1.0.0 installation format.
* The interactive mode has been significantly differentiated from the file standard input.

### Fixed

* Each number argument must be a single line argument.
* Fix negative lowercase hexadecimal number detection when input is signed.

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
