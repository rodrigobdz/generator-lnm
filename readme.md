# generator-lnm [![Build Status](https://travis-ci.com/rodrigobdz/generator-lnm.svg?branch=master)](https://travis-ci.com/rodrigobdz/generator-lnm)

> Scaffold out a node module

Optionally with a [CLI](http://en.wikipedia.org/wiki/Command-line_interface).

This is what I use for [my own modules](https://www.npmjs.com/~rodrigobdz).

![Usage screenshot](screenshot.png)

## Install

```sh
$ npm install --global yo generator-lnm
```

## Usage

With [yo](https://github.com/yeoman/yo):

```sh
$ yo lnm
```

There are multiple command-line options available:

```sh
$ yo lnm --help

  Usage:
    yo lnm [options]

  Options:
    --help          # Print the generator's options and usage
    --skip-cache    # Do not remember prompt answers                      Default: false
    --skip-install  # Do not automatically install dependencies           Default: false
    --org           # Publish to a GitHub organization account
    --cli           # Add a CLI
    --coverage      # Add code coverage with nyc
    --codecov       # Upload coverage to codecov.io (implies --coverage)
```

The `--org` option takes a string value (i.e. `--org=avajs`). All others are boolean flags and can be negated with the `no` prefix (i.e. `--no-codecov`). You will be prompted for any options not passed on the command-line.

## Tip

Use [chalk](https://github.com/sindresorhus/chalk) if you want colors in your CLI.

## License

[MIT](license) © [rodrigobdz](https://rodrigobdz.github.io)
