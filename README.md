# Numeris: A polyglot Roman numeral library and conversion utility

Numeris is a set of simple libraries and utilities for converting between
integers and Roman numerals. The goal is to serve as an educational playground
and comparison tool for various popular languages and ecosystems.

## Specification

### Requirements

Each implementation **must** implement the following:

* Idiomatic, **reusable library** that can be consumed through the platform's
  built-in or de facto standard dependency sharing mechanism
* Simple function to convert an integral value **between 1 and 3,999** to a
  Roman numeral
* Simple function to convert a Roman numeral **between 1 and 3,999** to an
  integral value
* **Unit tests** for the library, with at least 90% code coverage
* Be **thread-safe**

### Optional Features

Each implementation **should** also implement the following, to the extent
possible with the language/runtime/platform:

* Installable **command line interface** that can be installed through the same
  means, if possible, or through another tool common in that ecosystem
* Be **environment- and platform-agnostic**

#### Command line interface

If implemented, the CLI **must** support the following invocation syntax and
parameters:

```shell
Usage: numeris [options]

Numeris - a Roman numeral converter

Options:
  -V, --version           output the version number
  -i, --integer <number>  Convert the given integer value to a roman numeral
  -r, --roman <numeral>   Convert the given roman numeral to an integer value
  -d, --debug             Debugging output
  -b, --bare              Only output the result
  -h, --help              display help for command
```

## Implementations

The following are completed, in-progress, and planned implementations:

* [JavaScript](javascript/README.md) :white_check_mark:
* [Rust](rust/README.md) :white_check_mark:
* Go :soon:
* Python :soon:
* Java :soon:
