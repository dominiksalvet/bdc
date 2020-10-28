# nconv

[![CI status](https://github.com/dominiksalvet/nconv/workflows/CI/badge.svg)](https://github.com/dominiksalvet/nconv/actions)
[![GitPack](https://img.shields.io/badge/-GitPack-571997)](https://github.com/dominiksalvet/gitpack)
[![POSIX Shell](https://img.shields.io/badge/POSIX-Shell-111111)](https://pubs.opengroup.org/onlinepubs/9699919799/utilities/V3_chap02.html)

> Binary, decimal, and hexadecimal converter.

Nconv (number converter) is a simple and intuitive tool for converting among binary, decimal, and hexadecimal numbers. It was created with **programmers in mind**. Have a look at its sleek features and convince yourself:

* Smart conversions based on the first number
* Perfect support for **two's complement**
* Numbers may have arbitrary length

To ensure that nconv will work out of the box on as many systems as possible, it was designed as a very portable POSIX Shell script, which also means no need for compilation. Just **install and use** immediately.

## Install

Nconv supports [GitPack](https://github.com/dominiksalvet/gitpack). Local installation/update:

```sh
gitpack install github.com/dominiksalvet/nconv
```

## Usage

**Smart** conversion:

```
nconv <number>
```

> Rules: bin → dec, dec → bin, hex → dec.

**Manual base** conversion:

```
nconv -b/-d/-h -B/-D/-H <number>
```

> Input options are lowercase, output ones are uppercase.

**Manual signedness** conversion:

```
nconv -s/-u <number>
```

> Input is considered to be signed/unsigned.

**Manual width** conversion:

```
nconv -W <width> <number>
```

> Extend output to `<width>` digits. Respects signedness.

### Example

Example content.

## Useful Resources

* [support.md](support.md) – questions, answers, help
* [contributing.md](contributing.md) – how to get involve
* [license](license) – author and license
