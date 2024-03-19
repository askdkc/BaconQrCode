# Changelog

All notable changes to this project will be documented in this file, in reverse chronological order by release.

## 1.0.0 (2024-03-19)


### Features

* drop support for PHP &lt; 8.1 ([9e26f05](https://github.com/askdkc/BaconQrCode/commit/9e26f05b0f7f46f9df37a78316cf1443f626ae4e))
* make utf-8 eci prefix configurable ([#130](https://github.com/askdkc/BaconQrCode/issues/130)) ([8eba389](https://github.com/askdkc/BaconQrCode/commit/8eba389da071f396d71ddf034289093b9e4e9cae))


### Bug Fixes

* use non-locale aware format for scale and translate ([#100](https://github.com/askdkc/BaconQrCode/issues/100)) ([13ea674](https://github.com/askdkc/BaconQrCode/commit/13ea674432e798df82d6c56a10b2c0a2692ce3d1))
* **Version:** correct number of EC blocks for version 4 ([ed3734a](https://github.com/askdkc/BaconQrCode/commit/ed3734a9fcd1ca162aba79a5baef38bb4750218f))


### Miscellaneous Chores

* add test related files to .gitattributes ([2ca5870](https://github.com/askdkc/BaconQrCode/commit/2ca58705f6361673a658dbcb070940c65d04c7ac))
* bump github action "codecov/codecov-action" 3 =&gt; 4 ([bebae49](https://github.com/askdkc/BaconQrCode/commit/bebae498483f1dac210f260cb8f75660a2400fcd))
* fix ci deprecations ([db591bf](https://github.com/askdkc/BaconQrCode/commit/db591bf4d9757b2b68beda6dce3875b718d03aa7))
* fix ci deprecations, run phpcs on php 8.2 ([#140](https://github.com/askdkc/BaconQrCode/issues/140)) ([c759df7](https://github.com/askdkc/BaconQrCode/commit/c759df715aa86e34b9b83cd2b56b1df0cf4f21b2))

## 3.0.0 - 2022-03-14

### Changed

- Add strong php Types
- Fix spelling of DEFAULT_BYTE_MODE_ENCODING => DEFAULT_BYTE_MODE_ENCODING
- Constructor names of BlockPair
- Drop support for PHP < 8.1

## 2.0.7 - 2022-03-14

### Fixed

- [#102](https://github.com/Bacon/BaconQrCode/issues/102) Fix internal path for CompositeEye

## 2.0.6 - 2022-02-04

### Fixed

- Added tests back into release package.

## 2.0.5 - 2022-01-31

### Fixed

- [#70](https://github.com/Bacon/BaconQrCode/issues/79) Fix Imagick backend gradient generation.

## 2.0.2 - 2020-07-30

### Changed

- [#71](https://github.com/Bacon/BaconQrCode/issues/71) Upgrade phpunit.
- [#71](https://github.com/Bacon/BaconQrCode/issues/71) Allow tests in vendor bundles for Debian packaging.
- [#71](https://github.com/Bacon/BaconQrCode/issues/71) Update TravisCI config file.

## 2.0.1 - 2020-07-14

### Fixed

- [#69](https://github.com/Bacon/BaconQrCode/pull/69) SimpleCircleEye Class not working properly.

## 2.0.0 - 2018-04-25

### Added

- [#25](https://github.com/Bacon/BaconQrCode/pull/25) allows for setting a more compact text output

- CHANGELOG.md added (how meta)

- Allows more complex shapes for modules

- Allows setting a gradient for the foreground

- Allows transparent backgrounds and alpha channel on all colors

### Changed

- Minimum PHP version changed to 7.1

- Imagick renderer now allows setting different output formats

- New optimized SVG renderer

### Deprecated

- Nothing.

### Removed

- Legacy ZF module support removed

### Fixed

- Non-release files are excluded from composer packages
