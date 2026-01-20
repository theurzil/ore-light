# Changelog

## [0.10.0](https://github.com/theurzil/ore-light/compare/v0.17.3...v0.10.0) (2026-01-20)


### ⚠ BREAKING CHANGES

* drop Windows support and implement XDG Base Directory Specification ([#19](https://github.com/theurzil/ore-light/issues/19))

### Features

* add compact index support with cache freshness optimization ([dba03fb](https://github.com/theurzil/ore-light/commit/dba03fb87e1ef464f9b5fb9aa2678b1e95b173fe))
* Add gem source fallback mechanism for v0.1.1 ([df0af4f](https://github.com/theurzil/ore-light/commit/df0af4f2eefec288ecb605dbfa189cca26b536ac))
* add gemspec directive support ([378d6b3](https://github.com/theurzil/ore-light/commit/378d6b3d41bb3f9fdb475fcf2ebd99150e90aa60))
* add interactive TUI for outdated command with performance improvements ([7705ed3](https://github.com/theurzil/ore-light/commit/7705ed342dc3ae68991730c9e51f2165f99b0e00))
* Add ore audit licenses command ([02c21bd](https://github.com/theurzil/ore-light/commit/02c21bdf1cbb347496468e4afa7e47fc6a27b419))
* Add ore browse command ([59270ec](https://github.com/theurzil/ore-light/commit/59270ecf2ef429f174b852c3dfdc21da39b94584))
* Add ore gems command ([0812ecf](https://github.com/theurzil/ore-light/commit/0812ecfa2d46e8b9ac2d8ea1ad6dc3466d75644c))
* Add ore open command ([d38ed8d](https://github.com/theurzil/ore-light/commit/d38ed8d5d7e0b95bdcedb129aa812d4d8edd523a))
* Add ore pristine command ([43caf97](https://github.com/theurzil/ore-light/commit/43caf97598a4de3cacd65135a994dc08c7edc491))
* Add ore search command ([a57dc88](https://github.com/theurzil/ore-light/commit/a57dc88595a8e4e910282a314b998f785d848538))
* Add ore stats command ([f983553](https://github.com/theurzil/ore-light/commit/f983553723623a10a4be7371c653d319d8304c41))
* Add ore why command ([271ce3a](https://github.com/theurzil/ore-light/commit/271ce3aa2467514b1b208f7580d802106088be0d))
* add self-update command ([9077b93](https://github.com/theurzil/ore-light/commit/9077b93c923aa5581db7a8a52c04c13bc4969ea9))
* add structured logging with slog ([46b29b8](https://github.com/theurzil/ore-light/commit/46b29b847013680a357fb9588941e834e651e1a1))
* Default mage install to ~/.local/bin for better UX ([d7d7c73](https://github.com/theurzil/ore-light/commit/d7d7c732bed5880d961a9964c279ea8dc6c698bc))
* Display post-install messages after gem installation ([e4e3288](https://github.com/theurzil/ore-light/commit/e4e328883730d1774fe3dd36d28483b240b51c09))
* drop Windows support and implement XDG Base Directory Specification ([#19](https://github.com/theurzil/ore-light/issues/19)) ([a713d55](https://github.com/theurzil/ore-light/commit/a713d55425bb34e9e2cf7b55927f0e3c729944c8))
* enhance browse command with summaries and detail view ([adf7acf](https://github.com/theurzil/ore-light/commit/adf7acf0915b4f3bb964ad08df2c046b3659e97c))
* export default command wrappers via internal/runtime package ([#29](https://github.com/theurzil/ore-light/issues/29)) ([d5df403](https://github.com/theurzil/ore-light/commit/d5df40350d69e14f117d788300d50e85520971f1))
* improve lock mechanism to work with bundler 4 ([#42](https://github.com/theurzil/ore-light/issues/42)) ([a4bacdf](https://github.com/theurzil/ore-light/commit/a4bacdf328abbc463f927489b17f30e236908034))
* migrate from tinyrange/pubgrub to pubgrub-go ([b61091c](https://github.com/theurzil/ore-light/commit/b61091c55ef6fa532b6175ff3fd79f76a114f018))
* refactor all command handlers into commands package ([#27](https://github.com/theurzil/ore-light/issues/27)) ([b13dce9](https://github.com/theurzil/ore-light/commit/b13dce964fca6e962f28c915af4a794de36f15db))
* replace exec git commands with go-git library for shallow clone support ([134e9a6](https://github.com/theurzil/ore-light/commit/134e9a611641ca567bbd1e9ad8a52cf7477a9b2e))
* Resolve all TODO items in codebase ([0e5b785](https://github.com/theurzil/ore-light/commit/0e5b785b0c6f9a39a0f6962ab8b869eadfb7f3b3))
* **sources:** add mirrors and conditional downloads ([b6116da](https://github.com/theurzil/ore-light/commit/b6116da233ff46e715d809b2bf4b61d94b9ee018))
* unify vendor dir detection with BUNDLE_PATH support ([6704748](https://github.com/theurzil/ore-light/commit/67047486b67df006a75bed332d2ac467b0e67cc7))
* update gemlock format and fix scope ([#35](https://github.com/theurzil/ore-light/issues/35)) ([8af7c55](https://github.com/theurzil/ore-light/commit/8af7c5570b5791b3897a4fbf281e761486c856e4))
* upgrade to ruby-extension-go v0.1.0 with tool checking ([651ae6d](https://github.com/theurzil/ore-light/commit/651ae6defef5dfce0e26d1b52158b33123bbce4d))
* use global gems by default like Bundler (no Ruby required) ([a93795a](https://github.com/theurzil/ore-light/commit/a93795a707f3982fb3a50cf43da197c11ad6232f))


### Bug Fixes

* Add Bundler-compatible installation paths and config command ([3647131](https://github.com/theurzil/ore-light/commit/36471314a7cffc7b4a1557d5ec7c63398c67af1e))
* Add missing go.sum entries for bubbles dependencies ([eb653cc](https://github.com/theurzil/ore-light/commit/eb653cc46dbb3617fce70d554b8446392462fdd8))
* avoid mutation of gnu/musl ([be45de5](https://github.com/theurzil/ore-light/commit/be45de53eb08c8548c0566486bdbfcb40771f4fe))
* bug in github fetch and improve downloader. ([#34](https://github.com/theurzil/ore-light/issues/34)) ([2800cf4](https://github.com/theurzil/ore-light/commit/2800cf4210f310290f0b52248079b3cdb35d00b9))
* correct ore exec description - requires bundle exec ([5595f66](https://github.com/theurzil/ore-light/commit/5595f66f55dc47da9abc3d01a2254e0927fd497f))
* detect gem paths for mise/asdf/rbenv version managers ([354afb1](https://github.com/theurzil/ore-light/commit/354afb14cea325682455a1649ee23bc36b9f3bd5))
* embed release builds directly in release-please workflow ([3c8dcef](https://github.com/theurzil/ore-light/commit/3c8dcef00b68d8c87e17e7abdc5b503758915141))
* exit non-zero on extension failures and support version-constrained build deps ([#39](https://github.com/theurzil/ore-light/issues/39)) ([218e976](https://github.com/theurzil/ore-light/commit/218e976e137972fe24b6502738af656c20ca62ab))
* fix detection version in docker ([ee583d7](https://github.com/theurzil/ore-light/commit/ee583d71f74a5fb7a27e555429da14380c32ee09))
* increase download timeout to 2.5 minutes for large gems ([00e77c1](https://github.com/theurzil/ore-light/commit/00e77c1d67151bd5d7c26cb110ef13d3e8f156a5))
* Linux libc variant (gnu/musl) - platform selection ([#49](https://github.com/theurzil/ore-light/issues/49)) ([6c950bf](https://github.com/theurzil/ore-light/commit/6c950bfc29c7ce6ade5d46e7b8742ec0dafcfbf5))
* match bundler 4 structure ([#46](https://github.com/theurzil/ore-light/issues/46)) ([cef507d](https://github.com/theurzil/ore-light/commit/cef507db2321af2fe315c3ffa52bae8bd452d339))
* mirror bundler install detection for native gems ([#53](https://github.com/theurzil/ore-light/issues/53)) ([434a1d0](https://github.com/theurzil/ore-light/commit/434a1d0a4435043252128f3678f9d38f5933a0a1))
* prevent path gem infinite recursion and add gem environment for extensions ([742a745](https://github.com/theurzil/ore-light/commit/742a745de257388a6d2750b37d68eaf41a024445))
* re-export default command wrappers from commands package to avoid internal/ import restrictions ([1f8c117](https://github.com/theurzil/ore-light/commit/1f8c117e7884ae72aafa206d8441c51f8897e3d8))
* relax Go version requirement to 1.25 ([86738e1](https://github.com/theurzil/ore-light/commit/86738e1f3f695102dc86c652bcdc0bb770243cf0))
* respect configured Gemfile sources in resolver ([b8fa602](https://github.com/theurzil/ore-light/commit/b8fa60213377dff0e4d2ce6e6736f4b83cb2cd73))
* trigger release ([5690de3](https://github.com/theurzil/ore-light/commit/5690de3364035dbcc34a142ccebf67e0dba6c2cd))
* trigger Release workflow after release-please creates release ([6f8f612](https://github.com/theurzil/ore-light/commit/6f8f6122642ac976f7df633cc9d6b4a0cc9cd36b))
* trigger release workflow on release events ([c407dec](https://github.com/theurzil/ore-light/commit/c407dec81ccc39212ec069f6e0686bdd5de37005))
* unify config resolution and CLI help ([#32](https://github.com/theurzil/ore-light/issues/32)) ([5f93327](https://github.com/theurzil/ore-light/commit/5f9332765ea8d6d8f795fcec324f100ef82e9d5d))
* update syntax ([807b983](https://github.com/theurzil/ore-light/commit/807b983ae7a26830e11b540b1f8d6a87821d8a91))

## [0.17.3](https://github.com/contriboss/ore-light/compare/v0.17.2...v0.17.3) (2026-01-15)


### Bug Fixes

* match bundler 4 structure ([#46](https://github.com/contriboss/ore-light/issues/46)) ([cef507d](https://github.com/contriboss/ore-light/commit/cef507db2321af2fe315c3ffa52bae8bd452d339))

## [0.17.2](https://github.com/contriboss/ore-light/compare/v0.17.1...v0.17.2) (2026-01-13)


### Bug Fixes

* avoid mutation of gnu/musl ([be45de5](https://github.com/contriboss/ore-light/commit/be45de53eb08c8548c0566486bdbfcb40771f4fe))

## [0.17.1](https://github.com/contriboss/ore-light/compare/v0.17.0...v0.17.1) (2026-01-13)


### Bug Fixes

* trigger release ([5690de3](https://github.com/contriboss/ore-light/commit/5690de3364035dbcc34a142ccebf67e0dba6c2cd))

## [0.17.0](https://github.com/contriboss/ore-light/compare/v0.16.1...v0.17.0) (2026-01-13)


### Features

* improve lock mechanism to work with bundler 4 ([#42](https://github.com/contriboss/ore-light/issues/42)) ([a4bacdf](https://github.com/contriboss/ore-light/commit/a4bacdf328abbc463f927489b17f30e236908034))

## [0.16.1](https://github.com/contriboss/ore-light/compare/v0.16.0...v0.16.1) (2026-01-05)


### Bug Fixes

* exit non-zero on extension failures and support version-constrained build deps ([#39](https://github.com/contriboss/ore-light/issues/39)) ([218e976](https://github.com/contriboss/ore-light/commit/218e976e137972fe24b6502738af656c20ca62ab))

## [0.16.0](https://github.com/contriboss/ore-light/compare/v0.15.1...v0.16.0) (2026-01-05)


### Features

* replace exec git commands with go-git library for shallow clone support ([134e9a6](https://github.com/contriboss/ore-light/commit/134e9a611641ca567bbd1e9ad8a52cf7477a9b2e))


### Bug Fixes

* increase download timeout to 2.5 minutes for large gems ([00e77c1](https://github.com/contriboss/ore-light/commit/00e77c1d67151bd5d7c26cb110ef13d3e8f156a5))

## [0.15.1](https://github.com/contriboss/ore-light/compare/v0.15.0...v0.15.1) (2026-01-04)


### Bug Fixes

* fix detection version in docker ([ee583d7](https://github.com/contriboss/ore-light/commit/ee583d71f74a5fb7a27e555429da14380c32ee09))

## [0.15.0](https://github.com/contriboss/ore-light/compare/v0.14.2...v0.15.0) (2026-01-04)


### Features

* update gemlock format and fix scope ([#35](https://github.com/contriboss/ore-light/issues/35)) ([8af7c55](https://github.com/contriboss/ore-light/commit/8af7c5570b5791b3897a4fbf281e761486c856e4))

## [0.14.2](https://github.com/contriboss/ore-light/compare/v0.14.1...v0.14.2) (2026-01-04)


### Bug Fixes

* bug in github fetch and improve downloader. ([#34](https://github.com/contriboss/ore-light/issues/34)) ([2800cf4](https://github.com/contriboss/ore-light/commit/2800cf4210f310290f0b52248079b3cdb35d00b9))
* unify config resolution and CLI help ([#32](https://github.com/contriboss/ore-light/issues/32)) ([5f93327](https://github.com/contriboss/ore-light/commit/5f9332765ea8d6d8f795fcec324f100ef82e9d5d))

## [0.14.1](https://github.com/contriboss/ore-light/compare/v0.14.0...v0.14.1) (2026-01-01)


### Bug Fixes

* re-export default command wrappers from commands package to avoid internal/ import restrictions ([1f8c117](https://github.com/contriboss/ore-light/commit/1f8c117e7884ae72aafa206d8441c51f8897e3d8))

## [0.14.0](https://github.com/contriboss/ore-light/compare/v0.13.0...v0.14.0) (2026-01-01)


### Features

* export default command wrappers via internal/runtime package ([#29](https://github.com/contriboss/ore-light/issues/29)) ([d5df403](https://github.com/contriboss/ore-light/commit/d5df40350d69e14f117d788300d50e85520971f1))

## [0.13.0](https://github.com/contriboss/ore-light/compare/v0.12.0...v0.13.0) (2026-01-01)


### Features

* refactor all command handlers into commands package ([#27](https://github.com/contriboss/ore-light/issues/27)) ([b13dce9](https://github.com/contriboss/ore-light/commit/b13dce964fca6e962f28c915af4a794de36f15db))

## [0.12.0](https://github.com/contriboss/ore-light/compare/v0.11.0...v0.12.0) (2025-12-17)


### Features

* **sources:** add mirrors and conditional downloads ([b6116da](https://github.com/contriboss/ore-light/commit/b6116da233ff46e715d809b2bf4b61d94b9ee018))

## [0.11.0](https://github.com/contriboss/ore-light/compare/v0.10.0...v0.11.0) (2025-12-17)


### Features

* unify vendor dir detection with BUNDLE_PATH support ([6704748](https://github.com/contriboss/ore-light/commit/67047486b67df006a75bed332d2ac467b0e67cc7))


### Bug Fixes

* detect gem paths for mise/asdf/rbenv version managers ([354afb1](https://github.com/contriboss/ore-light/commit/354afb14cea325682455a1649ee23bc36b9f3bd5))

## [0.10.0](https://github.com/contriboss/ore-light/compare/v0.9.1...v0.10.0) (2025-11-21)


### ⚠ BREAKING CHANGES

* drop Windows support and implement XDG Base Directory Specification ([#19](https://github.com/contriboss/ore-light/issues/19))

### Features

* drop Windows support and implement XDG Base Directory Specification ([#19](https://github.com/contriboss/ore-light/issues/19)) ([a713d55](https://github.com/contriboss/ore-light/commit/a713d55425bb34e9e2cf7b55927f0e3c729944c8))

## [0.9.1](https://github.com/contriboss/ore-light/compare/v0.9.0...v0.9.1) (2025-11-11)


### Bug Fixes

* relax Go version requirement to 1.25 ([86738e1](https://github.com/contriboss/ore-light/commit/86738e1f3f695102dc86c652bcdc0bb770243cf0))

## [0.9.0](https://github.com/contriboss/ore-light/compare/v0.8.0...v0.9.0) (2025-11-11)


### Features

* add interactive TUI for outdated command with performance improvements ([7705ed3](https://github.com/contriboss/ore-light/commit/7705ed342dc3ae68991730c9e51f2165f99b0e00))
* add structured logging with slog ([46b29b8](https://github.com/contriboss/ore-light/commit/46b29b847013680a357fb9588941e834e651e1a1))

## [0.8.0](https://github.com/contriboss/ore-light/compare/v0.7.3...v0.8.0) (2025-11-01)


### Features

* enhance browse command with summaries and detail view ([adf7acf](https://github.com/contriboss/ore-light/commit/adf7acf0915b4f3bb964ad08df2c046b3659e97c))

## [0.7.3](https://github.com/contriboss/ore-light/compare/v0.7.2...v0.7.3) (2025-11-01)


### Bug Fixes

* embed release builds directly in release-please workflow ([3c8dcef](https://github.com/contriboss/ore-light/commit/3c8dcef00b68d8c87e17e7abdc5b503758915141))

## [0.7.2](https://github.com/contriboss/ore-light/compare/v0.7.1...v0.7.2) (2025-11-01)


### Bug Fixes

* trigger Release workflow after release-please creates release ([6f8f612](https://github.com/contriboss/ore-light/commit/6f8f6122642ac976f7df633cc9d6b4a0cc9cd36b))

## [0.7.1](https://github.com/contriboss/ore-light/compare/v0.7.0...v0.7.1) (2025-11-01)


### Bug Fixes

* trigger release workflow on release events ([c407dec](https://github.com/contriboss/ore-light/commit/c407dec81ccc39212ec069f6e0686bdd5de37005))

## [0.7.0](https://github.com/contriboss/ore-light/compare/v0.6.0...v0.7.0) (2025-11-01)


### Features

* add self-update command ([9077b93](https://github.com/contriboss/ore-light/commit/9077b93c923aa5581db7a8a52c04c13bc4969ea9))


### Bug Fixes

* respect configured Gemfile sources in resolver ([b8fa602](https://github.com/contriboss/ore-light/commit/b8fa60213377dff0e4d2ce6e6736f4b83cb2cd73))

## [0.6.0](https://github.com/contriboss/ore-light/compare/v0.5.1...v0.6.0) (2025-11-01)


### Features

* add compact index support with cache freshness optimization ([dba03fb](https://github.com/contriboss/ore-light/commit/dba03fb87e1ef464f9b5fb9aa2678b1e95b173fe))
