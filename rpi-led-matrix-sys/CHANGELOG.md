# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## UNRELEASED

- While cross-compiling, pass the correct CC and CXX to the Makefile.

## [0.3.1](https://github.com/AidanWallace/rust-rpi-rgb-led-matrix/compare/pi-led-matrix-sys-v0.3.0...pi-led-matrix-sys-v0.3.1) (2026-05-02)


### Bug Fixes

* errs ([#9](https://github.com/AidanWallace/rust-rpi-rgb-led-matrix/issues/9)) ([648b940](https://github.com/AidanWallace/rust-rpi-rgb-led-matrix/commit/648b94042c266892915b2852a3e72f25005e9b5f))

## [0.3.0](https://github.com/AidanWallace/rust-rpi-rgb-led-matrix/compare/pi-led-matrix-sys-v0.2.1...pi-led-matrix-sys-v0.3.0) (2026-05-02)


### Features

* release ([ee36625](https://github.com/AidanWallace/rust-rpi-rgb-led-matrix/commit/ee36625ae24b3ff606b23cd369832936bb4105c7))


### Bug Fixes

* fix ci ([b194568](https://github.com/AidanWallace/rust-rpi-rgb-led-matrix/commit/b194568872c58170577e27f0770ac617104416ad))

## [0.2.1] - 2022-01-05

- tweaked categories and reduced the size of the package by excluding unneeded parts of the c++ library.

## [0.2.0] - 2022-01-05

- Took a lot of clippy suggestions. Added `#[must_use]` where it made sense.
  Most of the rest was documentation changes and moving from `unwrap` to `expect`.
- Enable static linking to `libstdc++` if requested via the feature `stdcpp-static-link`.
- Updated to 2021 edition.

## [0.1.4] - 2021-12-05

- update C++ submodule to top of tree

## [0.1.3] - 2021-12-05

- Build script improvements around the C++ git submodule

## [0.1.2] - 2021-12-04

- Fix C++ std lib linking issue

## [0.1.1] - 2021-12-04 (**YANKED**)

- Cosmetic README/documentation updates

## [0.1.0] - 2021-12-04 (**YANKED**)

- Initial release
