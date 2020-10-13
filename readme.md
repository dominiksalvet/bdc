# nconv

[![CI status](https://github.com/dominiksalvet/nconv/workflows/CI/badge.svg)](https://github.com/dominiksalvet/nconv/actions)
[![GitPack](https://img.shields.io/badge/-GitPack-571997)](https://github.com/dominiksalvet/gitpack)
[![POSIX Shell](https://img.shields.io/badge/POSIX-Shell-111111)](https://pubs.opengroup.org/onlinepubs/9699919799/utilities/V3_chap02.html)

> Binary, decimal and hexadecimal converter.

Nconv (number converter) is a simple and intuitive tool for converting among binary, decimal and hexadecimal numbers. It was designed as a portable Shell script, so that it can be run almost everywhere.

Nconv is also smart. In most cases, you don't need to state which conversion you are interested in. Just type a number and nconv will perform the conversion automatically. How convenient.

## Install

Nconv supports [GitPack](https://github.com/dominiksalvet/gitpack). Local installation/update:

```sh
gitpack install github.com/dominiksalvet/nconv
```

## Usage

**Automatic** number conversion:

```
nconv <number>
```

> Rules: bin → dec, dec 🡒 bin, hex ⟶ dec.

### Example

Example content.

## Useful Resources

* [support.md](support.md) – questions, answers, help
* [contributing.md](contributing.md) – how to get involve
* [license](license) – author and license
