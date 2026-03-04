# Changelog

## [2.0.0](https://github.com/kxiong0/external-dns-infoblox-webhook/compare/v1.7.0...v2.0.0) (2026-03-04)


### ⚠ BREAKING CHANGES

* Initial commit

### Features

* Add metrics for infoblox API calls ([a533e11](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/a533e112c3148f351fdc522af8ddf3296749a3d6))
* add NS record support ([#49](https://github.com/kxiong0/external-dns-infoblox-webhook/issues/49)) ([f15d8b4](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/f15d8b403f9b0fea14750718aba8975016898f51))
* Add support for extensible attributes ([#26](https://github.com/kxiong0/external-dns-infoblox-webhook/issues/26)) ([27b345d](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/27b345d7e7453d3bf9ab2d4b21627770e3ee84b5))
* Implement support for PTR records ([#22](https://github.com/kxiong0/external-dns-infoblox-webhook/issues/22)) ([ca1cbaf](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/ca1cbafb48379eecee06294f050f6f5cd2fec0cc))
* Infoblox paging support ([f457da8](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/f457da8a091c062b6c264157aca94519b2805eb8))
* Initial commit ([5629414](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/562941456f5a60be6c98de55aa3e5f54edf73e2f))
* make use_ttl configurable via INFOBLOX_USE_TTL environment variable ([#56](https://github.com/kxiong0/external-dns-infoblox-webhook/issues/56)) ([f6b8704](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/f6b8704b020f118ddbc901931c900cbad5dda08f))


### Bug Fixes

* continue on buildRecord error ([9f376ad](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/9f376ade7346f8c5d1fa508cbdc1117f3b1e673c))
* ptr search query ([#32](https://github.com/kxiong0/external-dns-infoblox-webhook/issues/32)) ([bbcb30d](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/bbcb30d70b902506d15f3dc42b1f7daa3eb02739))
* revert repo-name ([#30](https://github.com/kxiong0/external-dns-infoblox-webhook/issues/30)) ([6454728](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/64547289e9505f2cbece2a2c95b7f9aa1a0a25e0))
* show errors in webhook ([323c425](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/323c4257a19a4035c9b6c8daf45102bb7eb9383a))
* test release ([350ffd0](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/350ffd0d05e6f8160cca72eb575013099c667e42))
* test release, bump patch ([acaadca](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/acaadca8b481f022d4f08bb89688b539e0af491b))
* Update README with new defaults ([a05beef](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/a05beefdfff9fb76b551680cf57e35f437ff248f))


### Miscellaneous Chores

* **release:** release 1.0.0 ([c455745](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/c455745d66c2dc97c18ada49c737b527b4e0af2e))
* **release:** release 1.0.0 ([575afc5](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/575afc5b5ea375f244dc885b366ef1a2465519ca))
* **release:** release 1.1.0 ([243416e](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/243416ea79ca66f5da614d705e06528a106d2eb4))
* **release:** release 1.1.0 ([0c1b194](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/0c1b194e09d8f078c25844217c75d04ccf381a1f))
* **release:** release 1.1.1 ([534beb4](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/534beb40e4b9a43e5de60daa18d443ad23e12829))
* **release:** release 1.1.1 ([7b81fee](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/7b81fee502ad63d519ba8df895d0f0c1a4d9dd1e))
* **release:** release 1.2.0 ([#25](https://github.com/kxiong0/external-dns-infoblox-webhook/issues/25)) ([30ab566](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/30ab566dff6160ff35ba2792d3914487f361c55a))
* **release:** release 1.3.0 ([#27](https://github.com/kxiong0/external-dns-infoblox-webhook/issues/27)) ([dc845fe](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/dc845fe1af694868f1c7a31629236e3c15a92fa2))
* **release:** release 1.4.0 ([#28](https://github.com/kxiong0/external-dns-infoblox-webhook/issues/28)) ([3ca7d58](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/3ca7d58da800c224500f527ca1c7d6a014529d38))
* **release:** release 1.4.1 ([#31](https://github.com/kxiong0/external-dns-infoblox-webhook/issues/31)) ([c92ee6e](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/c92ee6e96b55507b03128cd895e260fc69634277))
* **release:** release 1.4.2 ([#33](https://github.com/kxiong0/external-dns-infoblox-webhook/issues/33)) ([9f29e5a](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/9f29e5ae53e45d2a6a3ae2cc5a18d3019c30d329))
* **release:** release 1.4.3 ([#38](https://github.com/kxiong0/external-dns-infoblox-webhook/issues/38)) ([e8133c1](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/e8133c17e2c218495fa9d49cc869c51a6455b68b))
* **release:** release 1.4.4 ([0697642](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/06976425822045adfd6837eb6c497a864180019d))
* **release:** release 1.5.0 ([#51](https://github.com/kxiong0/external-dns-infoblox-webhook/issues/51)) ([a2de1d4](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/a2de1d4b42a45f6b822c3af41fcdac434876a591))
* **release:** release 1.6.0 ([4e325b8](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/4e325b853013fcc82813a6d62b45ba8404aef118))
* **release:** release 1.7.0 ([#57](https://github.com/kxiong0/external-dns-infoblox-webhook/issues/57)) ([6352339](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/6352339dacf8e0a2666d62868801a2ed1c649baa))
* upgrade golangci-lint version ([21be821](https://github.com/kxiong0/external-dns-infoblox-webhook/commit/21be821735ab2e8a7f677914f3d4ed1fc726ba9b))

## [1.7.0](https://github.com/AbsaOSS/external-dns-infoblox-webhook/compare/v1.6.0...v1.7.0) (2025-10-29)


### Features

* make use_ttl configurable via INFOBLOX_USE_TTL environment variable ([#56](https://github.com/AbsaOSS/external-dns-infoblox-webhook/issues/56)) ([f6b8704](https://github.com/AbsaOSS/external-dns-infoblox-webhook/commit/f6b8704b020f118ddbc901931c900cbad5dda08f))

## [1.6.0](https://github.com/AbsaOSS/external-dns-infoblox-webhook/compare/v1.5.0...v1.6.0) (2025-09-30)


### Features

* Add metrics for infoblox API calls ([a533e11](https://github.com/AbsaOSS/external-dns-infoblox-webhook/commit/a533e112c3148f351fdc522af8ddf3296749a3d6))

## [1.5.0](https://github.com/AbsaOSS/external-dns-infoblox-webhook/compare/v1.4.4...v1.5.0) (2025-08-21)


### Features

* add NS record support ([#49](https://github.com/AbsaOSS/external-dns-infoblox-webhook/issues/49)) ([f15d8b4](https://github.com/AbsaOSS/external-dns-infoblox-webhook/commit/f15d8b403f9b0fea14750718aba8975016898f51))

## [1.4.4](https://github.com/AbsaOSS/external-dns-infoblox-webhook/compare/v1.4.3...v1.4.4) (2025-05-13)


### Bug Fixes

* Update README with new defaults ([a05beef](https://github.com/AbsaOSS/external-dns-infoblox-webhook/commit/a05beefdfff9fb76b551680cf57e35f437ff248f))

## [1.4.3](https://github.com/AbsaOSS/external-dns-infoblox-webhook/compare/v1.4.2...v1.4.3) (2025-04-01)


### Bug Fixes

* continue on buildRecord error ([9f376ad](https://github.com/AbsaOSS/external-dns-infoblox-webhook/commit/9f376ade7346f8c5d1fa508cbdc1117f3b1e673c))
* show errors in webhook ([323c425](https://github.com/AbsaOSS/external-dns-infoblox-webhook/commit/323c4257a19a4035c9b6c8daf45102bb7eb9383a))

## [1.4.2](https://github.com/AbsaOSS/external-dns-infoblox-webhook/compare/v1.4.1...v1.4.2) (2024-12-29)


### Bug Fixes

* ptr search query ([#32](https://github.com/AbsaOSS/external-dns-infoblox-webhook/issues/32)) ([bbcb30d](https://github.com/AbsaOSS/external-dns-infoblox-webhook/commit/bbcb30d70b902506d15f3dc42b1f7daa3eb02739))

## [1.4.1](https://github.com/AbsaOSS/external-dns-infoblox-webhook/compare/v1.4.0...v1.4.1) (2024-12-14)


### Bug Fixes

* revert repo-name ([#30](https://github.com/AbsaOSS/external-dns-infoblox-webhook/issues/30)) ([6454728](https://github.com/AbsaOSS/external-dns-infoblox-webhook/commit/64547289e9505f2cbece2a2c95b7f9aa1a0a25e0))

## [1.4.0](https://github.com/AbsaOSS/external-dns-infoblox-webhook/compare/v1.3.0...v1.4.0) (2024-12-12)


### Features

* Add support for extensible attributes ([#26](https://github.com/AbsaOSS/external-dns-infoblox-webhook/issues/26)) ([27b345d](https://github.com/AbsaOSS/external-dns-infoblox-webhook/commit/27b345d7e7453d3bf9ab2d4b21627770e3ee84b5))


### Miscellaneous Chores

* **release:** release 1.3.0 ([#27](https://github.com/AbsaOSS/external-dns-infoblox-webhook/issues/27)) ([dc845fe](https://github.com/AbsaOSS/external-dns-infoblox-webhook/commit/dc845fe1af694868f1c7a31629236e3c15a92fa2))

## [1.3.0](https://github.com/AbsaOSS/external-dns-infoblox-webhook/compare/v1.2.0...v1.3.0) (2024-12-12)


### Features

* Add support for extensible attributes ([#26](https://github.com/AbsaOSS/external-dns-infoblox-webhook/issues/26)) ([27b345d](https://github.com/AbsaOSS/external-dns-infoblox-webhook/commit/27b345d7e7453d3bf9ab2d4b21627770e3ee84b5))

## [1.2.0](https://github.com/AbsaOSS/external-dns-infoblox-webhook/compare/v1.1.1...v1.2.0) (2024-11-06)


### Features

* Implement support for PTR records ([#22](https://github.com/AbsaOSS/external-dns-infoblox-webhook/issues/22)) ([ca1cbaf](https://github.com/AbsaOSS/external-dns-infoblox-webhook/commit/ca1cbafb48379eecee06294f050f6f5cd2fec0cc))

## [1.1.1](https://github.com/AbsaOSS/external-dns-infoblox-webhook/compare/v1.1.0...v1.1.1) (2024-06-06)


### Bug Fixes

* test release ([350ffd0](https://github.com/AbsaOSS/external-dns-infoblox-webhook/commit/350ffd0d05e6f8160cca72eb575013099c667e42))

## [1.1.0](https://github.com/AbsaOSS/external-dns-infoblox-webhook/compare/v1.0.0...v1.1.0) (2024-06-05)


### Features

* Infoblox paging support ([f457da8](https://github.com/AbsaOSS/external-dns-infoblox-webhook/commit/f457da8a091c062b6c264157aca94519b2805eb8))

## 1.0.0 (2024-05-28)


### ⚠ BREAKING CHANGES

* Initial commit

### Features

* Initial commit ([5629414](https://github.com/AbsaOSS/external-dns-infoblox-webhook/commit/562941456f5a60be6c98de55aa3e5f54edf73e2f))
