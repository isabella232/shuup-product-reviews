# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

Enter here all the changes made to the development version

### Fixed

- Fix issue that was not rendering starts in vendor reviews with options

## [1.0.1] - 2020-09-04

- Fix vendor reviews serializer which defined while excluding it
  (defining and excluding is not possible)


## [1.0.0] - 2020-08-07

Add Shuup 2.0 support. Not backwards compatible with 1.x version.

For patching old releases use "shuup1" branch.

## [0.6.4] - 2020-07-24

Last stable release for Shuup 1

- Add option for marketplace staff to define options for vendior reviews.
  These options can be used to categorize/group reviews. For example some
  options could be "Delivery", "Service Quality", "Service Price" etc... after
  the customer can leave review separately for each option.

## [0.6.0] - 2020-01-16

### Added

- Add util to render vendor reviews
- Add REST API endpoints for vendor reviews

### Changed

- Improve caches around vendor reviews
- Make orders available for review when paid instead of completed
