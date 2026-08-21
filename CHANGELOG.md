# Changelog

All notable changes to this project will be documented in this file. See [commit-and-tag-version](https://github.com/Unity-Billal-mesloub/commit-and-tag-version) for commit guidelines.

## [13.1.2](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v13.1.1...v13.1.2) (2026-07-28)


### Bug Fixes

* **yaml:** preserve long scalar lines ([issues](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues)) ([8b968bc](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/8b968bc1d98d85134c91efe66727bc2e1823a997))

## [13.1.1](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v13.1.0...v13.1.1) (2026-07-28)


### Bug Fixes

* Fix issue where prereleases were calculated from the wrong base (fixes [#310](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues/310)) ([1261803](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/12618033a5b1a6c8bf3fd2aa65ceb062b6180c3a))

## [13.1.0](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v13.0.0...v13.1.0) (2026-07-21)


### Features

* support ESM configuration files ([#306](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues)) ([9e0e5ab](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/9e0e5ab7ec8cf8a465b63d3858634126cd040542))

## [13.0.0](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v12.7.3...v13.0.0) (2026-07-18)


### ⚠ BREAKING CHANGES

* Update all conventional-changelog dependencies to their modern version. There are a few breaking changes that will affect users with custom presets, please see MIGRATION.md. This also raises the node minimum to node 22.
* This package is now pure ESM. CLI uses should be unaffected. This raises the minimum engine to 20.19, and anyone using require will need to `require('commit-and-tag-version').default`

### deps

* Update all conventional-changelog dependencies to their modern version. There are a few breaking changes that will affect users with custom presets, please see MIGRATION.md. This also raises the node minimum to node 22. ([c2d26bf](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/c2d26bf0b5692de6c357104613557f5bd41c95da))


### Bug Fixes

* **maven:** preserve comments in pom.xml ([#294](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues)) ([cbb6010](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/cbb60100f194877924d9cb98587aa8b2591b8318))


### Code Refactoring

* This package is now pure ESM. CLI uses should be unaffected. This raises the minimum engine to 20.19, and anyone using require will need to `require('commit-and-tag-version').default` ([89ba82e](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/89ba82eae4e2a167a5272c88a51d24a4e0a6b5da))

## [12.7.3](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v12.7.2...v12.7.3) (2026-03-18)


### Bug Fixes

* update release workflow for npm OIDC trusted publishing ([#281](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues/281)) ([d0e3408](https://github.com/absolute-version/commit-and-tag-version/commit/d0e3408a17ad9e20ab2e7d9b187d0a22da012cf7))

## [12.7.2](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v12.7.1...v12.7.2) (2026-03-18)


### Bug Fixes

* **maven:** Preserve XML attributes when updating pom.xml files ([issues](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues)) ([81b4f98](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/81b4f98319b88793f406139aa102d17a422cb8de))

## [12.7.1](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v12.7.0...v12.7.1) (2026-03-18)


### Bug Fixes

* 🐛 updating dependency fast-xml-parser ([issues](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues)) ([dac372b](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/dac372bfa8b8b124a1e9a8760074a86a641476f9))

## [12.7.0](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v12.6.1...v12.7.0) (2026-03-17)


### Features

* add --noBumpWhenEmptyChanges flag ([issues](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues/274)) ([b60fb23](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/b60fb237b78622a5d523423d1b40e87aeb8631b5))


### Bug Fixes

* make prerelease-flag work with gradle files ([issues](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues)) ([24e2f02](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/24e2f028ac5634f278bcd2980d87faabd70647e4))

## [12.6.1](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v12.6.0...v12.6.1) (2025-12-01)


### Bug Fixes

* **bump:** auto-increment prerelease when tag already exists ([issues](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues)) ([75d69a6](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/75d69a6a63c545062525c5566b60d2903a4666f4))
* use `fast-xml-parser` to parse and build XML. This substantially reduces the bundle size. ([#234](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues)) ([6075f4b](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/6075f4bb1e34d55fc403a3b5b49390af0e760684))

## [12.6.0](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v12.5.2...v12.6.0) (2025-08-27)


### Features

* add --config option to allow custom config file path ([issues](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues)) ([3958e68](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/3958e688a60df4f1ba46137d1f4147a65817c8d7))

## [12.5.2](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v12.5.1...v12.5.2) (2025-07-30)


### Bug Fixes

* Correct use of fs, so we no longer emit a deprecation warning for `fs.F_OK` ([7fe66bb](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/7fe66bb590103a593ecacabeb8effb8716862517)), closes [issues](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues)

## [12.5.1](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v12.5.0...v12.5.1) (2025-04-09)


### Bug Fixes

* ignore other prerelease tags when finding latest tag ([issues](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues)) ([issues](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues)) ([1bcdf40](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/1bcdf408cac54aff37aa4d5611444f6877aad6f9))

## [12.5.0](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v12.4.4...v12.5.0) (2024-10-10)


### Features

* **python:** add poetry support ([issues](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues)) ([01f08e9](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/01f08e9093e255f81394c97bcac59e057f5717dc))

## [12.4.4](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v12.4.3...v12.4.4) (2024-09-15)


### Bug Fixes

* sanitize double quotes result from stdout ([issues](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues)) ([8dbeb79](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/8dbeb794b960c6ea27527353ad2c55884f48b469))

## [12.4.3](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v12.4.2...v12.4.3) (2024-09-09)


### Bug Fixes

* Correct issue where downstream dependency would throw `options.debug is not a function` ([4280bcf](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/4280bcf102b78d1995b24ec9238219db81730ebd))

## [12.4.2](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v12.4.1...v12.4.2) (2024-08-25)


### Bug Fixes

* **deps:** update dependency conventional-changelog to v4 ([#176](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues/)) ([8d15fc7](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/8d15fc788edc2fd5d901ccbbbacb3452eabc3091))

## [12.4.1](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v12.4.0...v12.4.1) (2024-04-28)


### Bug Fixes

* raise the 'openapi'-updater to a higher order of precedence above the 'yaml'-updater ([issues](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues)) ([37fe178](https://github.com/absolute-version/commit-and-tag-version/commit/37fe178fdba051c665414565fe4b0e61336aff18))

## [12.4.0](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v12.3.0...v12.4.0) (2024-04-19)


### Features

* Add OpenAPI version support ([issues](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues)) ([007b1b0](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/007b1b0386651f2fbd6e8a9f552a2a34702086ca))

## [12.3.0](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v12.2.0...v12.3.0) (2024-04-19)


### Features

* **updater:** add YAML support ([issues](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues)) ([b9dccc2](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/b9dccc23ec05e4026899c676f3275d4dedf8c686))


### Bug Fixes

* Add debug messages for exclusions during bump lifecycle ([issues](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues)) ([a9191f2](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/a9191f293eb9302afb1093ad37e9fa076f6b37a2))

## [12.2.0](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v12.1.0...v12.2.0) (2024-01-15)


### Features

* **updater:** add maven pom.xml file support ([issues](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues), [issues](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues)) ([issues](https://github.com/absolute-version/commit-and-tag-version/issues/123)) ([6466beb](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/6466bebf849bbdcdaebf493a1ccce9670c469fde))

## [12.1.0](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v12.0.0...v12.1.0) (2024-01-06)


### Features

* Add signoff option ([issues](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues/120)) ([d107e38](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/d107e38eb906dfb21658d12803b7308f2e3dda7d))

## [12.0.0](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v11.3.0...v12.0.0) (2023-10-31)


### ⚠ BREAKING CHANGES

* Drop support for node 14, 16. Now supports node 18 and 20.

### Bug Fixes

* Drop support for node 14, 16. Now supports node 18 and 20. ([b1a58bc](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/b1a58bc2a786da48fbcec248204ff8631c79606e))
* preserve frontmatter when updating changelog  ([issues](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues)) ([abdcfe2](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/abdcfe295023f46c8724463940fff6a220434fad))

## [11.3.0](https://github.com/absolute-version/commit-and-tag-version/compare/v11.2.4...v11.3.0) (2023-10-10)


### Features

* **updater:** add .csproj file support ([issues](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues)) ([a96554c](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/a96554c9467bacdf6c9d898b223883ee32f63c15))

## [11.2.4](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v11.2.3...v11.2.4) (2023-10-02)


### Bug Fixes

* allow bump task to handle versions with build metadata ([33913ee](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/33913ee03bff2dfc26c9ffc942e1191c1f767949))
* handle invalid versions passed to releaseAs ([33913ee](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/33913ee03bff2dfc26c9ffc942e1191c1f767949))

## [11.2.3](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v11.2.2...v11.2.3) (2023-08-22)


### Bug Fixes

* **bump:** propagate the parserOpts from args to conventionalRecommendedBump, fixing an issue with custom headerPatterns ([issues](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues)) ([bc685be](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/bc685be46ca90417a03867717393bb9018e6036c))

## [11.2.2](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v11.2.1...v11.2.2) (2023-06-18)


### Bug Fixes

* **deps:** update dependency conventional-changelog-conventionalcommits to v6 ([285f5e7](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/285f5e7c9d415c029fe6b6f4781f6ccfa71a0151))
* **deps:** update dependency conventional-changelog-conventionalcommits to v6 ([#81](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues/81)) ([ab67fa4](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/ab67fa43b644f8078530ca7927054cd8cf5add77))
* **deps:** update dependency conventional-changelog-conventionalcommits to v6.1.0 ([39827d3](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/39827d386ce8c3dbad7605ef872975ebe48db72a))
* **deps:** update dependency conventional-changelog-conventionalcommits to v6.1.0 ([#86](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues/86)) ([a8580d5](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/a8580d5859c6c44ed82ac244eabad967eca0d4b8))
* **deps:** update dependency conventional-recommended-bump to v7 ([5978564](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/59785644f2cd7980139c49086f3ba662f63a7179))
* **deps:** update dependency conventional-recommended-bump to v7 ([#83](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues/83)) ([1c9f82e](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/1c9f82eca486dceda244d37f5264f992b9a5c57e))
* **deps:** update dependency git-semver-tags to v5 ([97e0237](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/97e0237d645e1686f96418a1f2d8dbd6bfeca90b))
* **deps:** update dependency git-semver-tags to v5 ([issues](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues)) ([46ea506](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/46ea506c5f2e5300f195462a6c2339cbe4b98fcb))

## [11.2.1](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v11.2.0...v11.2.1) (2023-04-05)


### Bug Fixes

* **dep:** add stringify-package to project source, removing the deprecation warning on npm install ([issues](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/issues)) ([3a959a7](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/3a959a7eba86ad42b98592167df7c67f00b661a0))

## [11.2.0](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v11.1.0...v11.2.0) (2023-03-15)


### Features

* implement detect pm name ([174a8bd](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/174a8bd00106dcc2a6b1c5bcb75bf3fbfd0317da))
* support config npmClient ([c33686a](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/c33686aec080162645466ed962d64133f71e4214))
* Support customizing the npm publish hint message with a new option: `npmPublishHint` ([1f77110](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/1f77110deefa8a394a37c421eb3d313f6c87aea5))

## [11.1.0](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v11.0.0...v11.1.0) (2023-02-14)


### Features

* Expose release count option ([40d27f8](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/40d27f8782c0621f6ec0ab796b4ae674ec6d43c8))
* replace the changelog if releaseCount = 0 ([d18af90](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/d18af9040fdc2a5798681fa747a43a71cb75e47b))


### Bug Fixes

* ensure git signatures are not present ([268800b](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/268800b3c5e01993902cb0df0d123ac8b3388359))

## [11.0.0](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v10.1.0...v11.0.0) (2023-01-17)


### ⚠ BREAKING CHANGES

* **deps:** update dependency conventional-changelog-conventionalcommits to v5. This is technically a breaking change for anyone relying on the exact formatting of the changelog, as it ensures that versions are always written with H2 headers.

### Bug Fixes

* **deps:** update dependency conventional-changelog-conventionalcommits to v5 ([b38e900](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/b38e900c2b8577b492b4bb42e88d327e80e663a4))
* **deps:** update dependency conventional-changelog-conventionalcommits to v5. This is technically a breaking change for anyone relying on the exact formatting of the changelog, as it ensures that versions are always written with H2 headers. ([ffa799a](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/ffa799aa335f9b912a224336cf2ea2537b8aa310))

## [10.1.0](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v10.0.1...v10.1.0) (2022-08-11)


### Features

* **options:** Expose parser and writer options from `conventional-commits-parser` and `conventional-commits-writer` ([185a461](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/185a461acc1caf947bf78dd2185f4687afad66fc))
* **updater:** add Gradle support ([0cf439f](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/0cf439fe4047ffa10d21196714c25517535b6302))


### Bug Fixes

* use correct param for dryRun check ([300b907](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/300b90777c5c8c9cca15f69122af1d41981ca47d))

### [10.0.1](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v10.0.0...v10.0.1) (2022-05-28)


### Bug Fixes

* No longer warn inappropriately when a custom updater is provided as an object ([5eb8886](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/5eb8886a56c6b14c13544192edb3d0e18f91184a))

## [10.0.0](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v9.6.0...v10.0.0) (2022-05-25)


### ⚠ BREAKING CHANGES

* Drop support for node 10 and 12, support node 16 and 18

### Bug Fixes

* **deps:** update dependency yargs to v17 ([d190c51](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/d190c51507026adefe640cdd75f0a643afd81b87))


### Build System

* Drop support for node 10 and 12, support node 16 and 18 ([0f75115](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/0f751158c2df9cbf7a2c16bef55a5de084f0d17d))

## [9.6.0](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/compare/v9.5.0...v9.6.0) (2022-05-25)


### Features

* **tag:** add an option to force tag replacement ([df5a94a](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/df5a94a978c6966e334ec0e4c9f082fae8deb4f9))


### Bug Fixes

* Combining both release-as and prerelease now doesn't break package ([5ecfa2e](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/5ecfa2e250e134dbfd3ce8d3c6e9d3be28f6f2b8))
* Fallback to git tag if no version in package file ([57e7091](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/57e70916c8afbce16347ed1f710984f5a483152a))
* No longer skips the commit if changelog and bump are both skipped but `commitAll` is set ([08a0121](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/08a01212f0eea7ee5e454adf560755df67234d2f))
* Use relative path from .gitignore to avoid files matching inappropriately ([d2491bc](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/d2491bc8b61a60cd438045ac409278f5b84621dd))
* When a custom updater reports a version other than the new computed semver, that version is now correctly reported in log output ([f2e83bf](https://github.com/Unity-Billal-mesloub/commit-and-tag-version/commit/f2e83bfac711ac5ba4de940d654269af69fc7312))


### Bug Fixes

* **deps:** update dependency conventional-changelog to v3.1.24 ([#677](https://www.github.com/conventional-changelog/standard-version/issues/677)) ([cc45036](https://www.github.com/conventional-changelog/standard-version/commit/cc45036d9960b6d83e0e850ccbbe8e8098d36ae6))
* **deps:** update dependency conventional-changelog-conventionalcommits to v4.5.0 ([#678](https://www.github.com/conventional-changelog/standard-version/issues/678)) ([6317d36](https://www.github.com/conventional-changelog/standard-version/commit/6317d36130767cfd85114ab9033a6f1ef110388d))
* **deps:** update dependency conventional-recommended-bump to v6.0.11 ([#679](https://www.github.com/conventional-changelog/standard-version/issues/679)) ([360789a](https://www.github.com/conventional-changelog/standard-version/commit/360789ab84957a67d3919cb28db1882cb68296fc))
* **deps:** update dependency find-up to v5 ([#651](https://www.github.com/conventional-changelog/standard-version/issues/651)) ([df8db83](https://www.github.com/conventional-changelog/standard-version/commit/df8db832327a751d5c62fe361b6ac2d2b5f66bf6))
