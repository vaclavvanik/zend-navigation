# Changelog

All notable changes to this project will be documented in this file, in reverse chronological order by release.

## 2.7.2 - TBD

### Added

- [#27](https://github.com/zendframework/zend-navigation/pull/27) adds and
  publishes the documentation to https://zendframework.github.io/zend-navigation/

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Nothing.

## 2.7.1 - 2016-04-08

### Added

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- This release removes the erroneous calls to `getViewHelperConfig()` in the
  `ConfigProvider` and `Module` classes.

## 2.7.0 - 2016-04-08

### Added

- [#26](https://github.com/zendframework/zend-navigation/pull/26) adds:
  - `Zend\Navigation\View\ViewHelperManagerDelegatorFactory`, which decorates
    the `ViewHelperManager` service to configure it using
    `Zend\Navigation\View\HelperConfig`.
  - `ConfigProvider`, which maps the default navigation factory and the
    navigation abstract factory, as well as the navigation view helper.
  - `Module`, which does the same as the above, but for zend-mvc
    applications.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- Nothing.

## 2.6.1 - 2016-03-21

### Added

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- [#25](https://github.com/zendframework/zend-navigation/pull/25) ups the
  minimum zend-view version to 2.6.5, to bring in a fix for a circular
  dependency issue in the navigation helpers.

## 2.6.0 - 2016-02-24

### Added

- Nothing.

### Deprecated

- Nothing.

### Removed

- Nothing.

### Fixed

- [#5](https://github.com/zendframework/zend-navigation/pull/5) and
  [#20](https://github.com/zendframework/zend-navigation/pull/20) update the
  code to be forwards compatible with zend-servicemanager v3.
