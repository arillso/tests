# Tests

## Description

Test Rules for an Ansible Role.

## Installation

Checkout this repository into a directory on your system or add it as a git
submodule to your project.

## Usage

### ansible-lint

Use ansible-lint with the options ``-R`` and ``-r <directory>``. E.g.

```Bash
  ansible-lint -R -r ./ansible-lint/ site.yml

```

### yaml-lint

Use yaml-lint with the options ``-c <directory>/yamllint.yml`` E.g.

```Bash
  ansible-lint -R -r ./yaml-lint/yamllint.yaml skeleton

```

## Changelog

### 0.2

* Remove trailing spaces

### 0.1

* First test version

## Author

* [Simon Bärlocher](https://sbaerlocher.ch)

## License

This project is under the MIT License. See the [LICENSE](https://sbaerlo.ch/licence) file for the full license text.

## Copyright

(c) 2017, Simon Bärlocher