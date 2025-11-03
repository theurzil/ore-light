# Changelog

## [0.6.0](https://github.com/theurzil/ore-light/compare/v0.8.0...v0.6.0) (2025-11-03)


### Features

* add compact index support with cache freshness optimization ([dba03fb](https://github.com/theurzil/ore-light/commit/dba03fb87e1ef464f9b5fb9aa2678b1e95b173fe))
* Add gem source fallback mechanism for v0.1.1 ([df0af4f](https://github.com/theurzil/ore-light/commit/df0af4f2eefec288ecb605dbfa189cca26b536ac))
* add gemspec directive support ([378d6b3](https://github.com/theurzil/ore-light/commit/378d6b3d41bb3f9fdb475fcf2ebd99150e90aa60))
* Add ore audit licenses command ([02c21bd](https://github.com/theurzil/ore-light/commit/02c21bdf1cbb347496468e4afa7e47fc6a27b419))
* Add ore browse command ([59270ec](https://github.com/theurzil/ore-light/commit/59270ecf2ef429f174b852c3dfdc21da39b94584))
* Add ore gems command ([0812ecf](https://github.com/theurzil/ore-light/commit/0812ecfa2d46e8b9ac2d8ea1ad6dc3466d75644c))
* Add ore open command ([d38ed8d](https://github.com/theurzil/ore-light/commit/d38ed8d5d7e0b95bdcedb129aa812d4d8edd523a))
* Add ore pristine command ([43caf97](https://github.com/theurzil/ore-light/commit/43caf97598a4de3cacd65135a994dc08c7edc491))
* Add ore search command ([a57dc88](https://github.com/theurzil/ore-light/commit/a57dc88595a8e4e910282a314b998f785d848538))
* Add ore stats command ([f983553](https://github.com/theurzil/ore-light/commit/f983553723623a10a4be7371c653d319d8304c41))
* Add ore why command ([271ce3a](https://github.com/theurzil/ore-light/commit/271ce3aa2467514b1b208f7580d802106088be0d))
* add self-update command ([9077b93](https://github.com/theurzil/ore-light/commit/9077b93c923aa5581db7a8a52c04c13bc4969ea9))
* Default mage install to ~/.local/bin for better UX ([d7d7c73](https://github.com/theurzil/ore-light/commit/d7d7c732bed5880d961a9964c279ea8dc6c698bc))
* Display post-install messages after gem installation ([e4e3288](https://github.com/theurzil/ore-light/commit/e4e328883730d1774fe3dd36d28483b240b51c09))
* enhance browse command with summaries and detail view ([adf7acf](https://github.com/theurzil/ore-light/commit/adf7acf0915b4f3bb964ad08df2c046b3659e97c))
* migrate from tinyrange/pubgrub to pubgrub-go ([b61091c](https://github.com/theurzil/ore-light/commit/b61091c55ef6fa532b6175ff3fd79f76a114f018))
* Resolve all TODO items in codebase ([0e5b785](https://github.com/theurzil/ore-light/commit/0e5b785b0c6f9a39a0f6962ab8b869eadfb7f3b3))
* upgrade to ruby-extension-go v0.1.0 with tool checking ([651ae6d](https://github.com/theurzil/ore-light/commit/651ae6defef5dfce0e26d1b52158b33123bbce4d))
* use global gems by default like Bundler (no Ruby required) ([a93795a](https://github.com/theurzil/ore-light/commit/a93795a707f3982fb3a50cf43da197c11ad6232f))


### Bug Fixes

* Add Bundler-compatible installation paths and config command ([3647131](https://github.com/theurzil/ore-light/commit/36471314a7cffc7b4a1557d5ec7c63398c67af1e))
* Add missing go.sum entries for bubbles dependencies ([eb653cc](https://github.com/theurzil/ore-light/commit/eb653cc46dbb3617fce70d554b8446392462fdd8))
* correct ore exec description - requires bundle exec ([5595f66](https://github.com/theurzil/ore-light/commit/5595f66f55dc47da9abc3d01a2254e0927fd497f))
* embed release builds directly in release-please workflow ([3c8dcef](https://github.com/theurzil/ore-light/commit/3c8dcef00b68d8c87e17e7abdc5b503758915141))
* prevent path gem infinite recursion and add gem environment for extensions ([742a745](https://github.com/theurzil/ore-light/commit/742a745de257388a6d2750b37d68eaf41a024445))
* respect configured Gemfile sources in resolver ([b8fa602](https://github.com/theurzil/ore-light/commit/b8fa60213377dff0e4d2ce6e6736f4b83cb2cd73))
* trigger Release workflow after release-please creates release ([6f8f612](https://github.com/theurzil/ore-light/commit/6f8f6122642ac976f7df633cc9d6b4a0cc9cd36b))
* trigger release workflow on release events ([c407dec](https://github.com/theurzil/ore-light/commit/c407dec81ccc39212ec069f6e0686bdd5de37005))
* update syntax ([807b983](https://github.com/theurzil/ore-light/commit/807b983ae7a26830e11b540b1f8d6a87821d8a91))

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
