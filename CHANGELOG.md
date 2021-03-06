# Gutsy Changelog

## 1.1.0

* Supports multiple API versions. `namespace_path` configuration replaced the
  short-lived `resource_namespace` config

## 1.0.3

* Adds `resource_namespace` configuration

## 1.0.2

* Make repo name configurable

## 1.0.1

* Fix missing line breaks in generated README.md

## 1.0.0

* Support multiple API versions and apps in one configuration file, allow configuring gem metadata. (#1)

### Breaking Changes

* The CLI API for `gutsy generate` has changed.

  In 0.1.0, you could do `gutsy generate AppName /path/to/schema.json /path/for/output/`.

  As of 1.0.0, gutsy now allows a much greater degree of customization, through a YAML configuration file.
  The interface is now `gutsy generate /path/to/gutsy/config.yml /path/for/output/`.

  See [`examples/config.yml`](examples/config.yml) for an example of a Gutsy configuration file.

## 0.1.0

* Initial release

