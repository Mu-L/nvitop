# Changelog

<!-- markdownlint-disable no-duplicate-header -->

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

------

## [Unreleased]

### Added

- Add `mypy` integration and update type annotations by [@XuehaiPan](https://github.com/XuehaiPan) in [#73](https://github.com/XuehaiPan/nvitop/pull/73).

### Changed

-

### Fixed

- Fix inappropriate exception catching in function `libcuda.cuDeviceGetUuid` by [@XuehaiPan](https://github.com/XuehaiPan).

### Removed

-

------

## [1.1.2] - 2023-04-11

### Fixed

- Further isolate the `CUDA_VISIBLE_DEVICES` parser in a subprocess by [@XuehaiPan](https://github.com/XuehaiPan) in [#70](https://github.com/XuehaiPan/nvitop/pull/70).

------

## [1.1.1] - 2023-04-07

### Fixed

- Fix MIG device support by [@XuehaiPan](https://github.com/XuehaiPan).

------

## [1.1.0] - 2023-04-07

### Added

- Support float number as snapshot interval that >= 0.25s by [@XuehaiPan](https://github.com/XuehaiPan) in [#67](https://github.com/XuehaiPan/nvitop/pull/67).
- Show more host metrics (e.g., used virtual memory, uptime) in CLI by [@XuehaiPan](https://github.com/XuehaiPan) in [#59](https://github.com/XuehaiPan/nvitop/pull/59).

### Changed

- Move `TTLCache` usage to CLI-only by [@XuehaiPan](https://github.com/XuehaiPan) in [#66](https://github.com/XuehaiPan/nvitop/pull/66).

### Fixed

- Respect `FORCE_COLOR` and `NO_COLOR` environment variables by [@XuehaiPan](https://github.com/XuehaiPan).

### Removed

- Drop Python 3.6 support by [@XuehaiPan](https://github.com/XuehaiPan) in [#56](https://github.com/XuehaiPan/nvitop/pull/56).

------

## [1.0.0] - 2023-02-01

### Added

- The first stable release of `nvitop` by [@XuehaiPan](https://github.com/XuehaiPan).

------

[Unreleased]: https://github.com/XuehaiPan/nvitop/compare/v1.1.2...HEAD
[1.1.2]: https://github.com/XuehaiPan/nvitop/releases/tag/v1.1.2
[1.1.1]: https://github.com/XuehaiPan/nvitop/releases/tag/v1.1.1
[1.1.0]: https://github.com/XuehaiPan/nvitop/releases/tag/v1.1.0
[1.0.0]: https://github.com/XuehaiPan/nvitop/releases/tag/v1.0.0