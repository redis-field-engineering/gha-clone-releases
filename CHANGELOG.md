# Changelog

## [1.10.0](https://github.com/redis-field-engineering/gha-clone-releases/compare/v1.9.0...v1.10.0) (2025-04-21)


### Features

* add auto-generating inputs ([7dc0b1f](https://github.com/redis-field-engineering/gha-clone-releases/commit/7dc0b1f99cff234dde85e06a8c7659d76b521fe7))
* add min_version and more debug output ([dc2d887](https://github.com/redis-field-engineering/gha-clone-releases/commit/dc2d887e4b1eda1c943e69d168484608984534ac))
* Added systematic copying of early-access releases ([53f0614](https://github.com/redis-field-engineering/gha-clone-releases/commit/53f061469028fc4f0e9732452f92462b7f6183d0))
* Always include `early-access` releases ([ce1641e](https://github.com/redis-field-engineering/gha-clone-releases/commit/ce1641e89c48d72e4f30a2c86f3daf6ebcf477fb))
* base on scratch image ([#13](https://github.com/redis-field-engineering/gha-clone-releases/issues/13)) ([25678da](https://github.com/redis-field-engineering/gha-clone-releases/commit/25678daf464067911ce26d56e1f64ec437bf6272))
* copy draft release from src ([#17](https://github.com/redis-field-engineering/gha-clone-releases/issues/17)) ([eb09597](https://github.com/redis-field-engineering/gha-clone-releases/commit/eb09597f45cb93af436643846c3cf79a7b9edeb7))
* move to poetry ([#15](https://github.com/redis-field-engineering/gha-clone-releases/issues/15)) ([1452522](https://github.com/redis-field-engineering/gha-clone-releases/commit/1452522f0939990d4f180058886c8912ae5c75c9))
* sort releases, proper comparison, limits ([2c02b93](https://github.com/redis-field-engineering/gha-clone-releases/commit/2c02b939627f63215c02398834d361195b85b1cb))
* support a separate token for destination  ([#185](https://github.com/redis-field-engineering/gha-clone-releases/issues/185)) ([17454d6](https://github.com/redis-field-engineering/gha-clone-releases/commit/17454d688fd0deeea68f7f07557c2b2eeefc13ca))
* support auth for asset download ([#29](https://github.com/redis-field-engineering/gha-clone-releases/issues/29)) ([72e76fa](https://github.com/redis-field-engineering/gha-clone-releases/commit/72e76fa103916de8a451af81b5dbd81594b5b213))
* support cloning assets to created releases ([#18](https://github.com/redis-field-engineering/gha-clone-releases/issues/18)) ([11c658e](https://github.com/redis-field-engineering/gha-clone-releases/commit/11c658e59405df8fd6bfece275b42a8b5d0e21f3))
* support Github Enterprise ([#40](https://github.com/redis-field-engineering/gha-clone-releases/issues/40)) ([3eb6682](https://github.com/redis-field-engineering/gha-clone-releases/commit/3eb6682f982d9964af35d61ab43ecc46eaf579bf))


### Bug Fixes

* actually do real comparison of releases ([8d6257d](https://github.com/redis-field-engineering/gha-clone-releases/commit/8d6257d297de49543138d2abcdc8172b383d6745))
* add more debugging output ([f089b81](https://github.com/redis-field-engineering/gha-clone-releases/commit/f089b813bd82ce031013395c583ff11996502bec))
* add packaging to requirements ([9965289](https://github.com/redis-field-engineering/gha-clone-releases/commit/99652895a28317d6339952bda959e9fe1ea9ceb7))
* adjust debug text to be more useful ([2b79026](https://github.com/redis-field-engineering/gha-clone-releases/commit/2b79026f3f4000fbf31c8c2824fa867f6fd65ed8))
* fix debug output and sets ([fca3eab](https://github.com/redis-field-engineering/gha-clone-releases/commit/fca3eab8f08f781262cb871b95681e9cde6c44e4))
* fix input ([ba7a7ff](https://github.com/redis-field-engineering/gha-clone-releases/commit/ba7a7ff94e1dd23f2a87d5949496a185c661cf63))
* fix issue with default branch ([51521ec](https://github.com/redis-field-engineering/gha-clone-releases/commit/51521ecdd685d1162341da636cfc74966cfae34b))
* fix issue with empty min version ([0849bfd](https://github.com/redis-field-engineering/gha-clone-releases/commit/0849bfdedfcefdc7e1131d000ef5352f737d31bf))
* handle exceptions better ([c500381](https://github.com/redis-field-engineering/gha-clone-releases/commit/c500381dc31a50ebca1493204fb18a84e20b7d78))
* make debug text more useful ([fde2af9](https://github.com/redis-field-engineering/gha-clone-releases/commit/fde2af950f908ef24b126fee195c6afe0d51a315))
* more debug info ([72e5057](https://github.com/redis-field-engineering/gha-clone-releases/commit/72e5057da2e4d331ac73018374bcad64e0de1111))
* pin to bullseye ([257aa64](https://github.com/redis-field-engineering/gha-clone-releases/commit/257aa6487d6fe82375fa337e15dbed8ac3b77349))
* **poetry:** update poetry to 1.5.0 ([#39](https://github.com/redis-field-engineering/gha-clone-releases/issues/39)) ([6726037](https://github.com/redis-field-engineering/gha-clone-releases/commit/6726037a65529796f3abd944aef1406113924013))
* tag with tag title ([5f4acad](https://github.com/redis-field-engineering/gha-clone-releases/commit/5f4acad51a5ebc25cd9757d96e6e11377a9322ca))
* tag with title ([26ac15c](https://github.com/redis-field-engineering/gha-clone-releases/commit/26ac15c71464ba195f4c14a28bc323f59b9a2ec0))
* update dockerfile to main ([903bf98](https://github.com/redis-field-engineering/gha-clone-releases/commit/903bf986ba9149ba70bb46d43a9da5290d33a73c))


### Documentation

* add andrewthetechie as a contributor for code, doc, and 2 more ([#21](https://github.com/redis-field-engineering/gha-clone-releases/issues/21)) ([78d29fb](https://github.com/redis-field-engineering/gha-clone-releases/commit/78d29fb84dcbb3586e905e224729924064c05e84))
* add jrbe228 as a contributor for bug, and ideas ([#31](https://github.com/redis-field-engineering/gha-clone-releases/issues/31)) ([b0ab4ef](https://github.com/redis-field-engineering/gha-clone-releases/commit/b0ab4ef2e5c6a86a4a276ca58ddf1628a0fdaf7e))
* add sebastienrospars as a contributor for code ([#186](https://github.com/redis-field-engineering/gha-clone-releases/issues/186)) ([13da9de](https://github.com/redis-field-engineering/gha-clone-releases/commit/13da9decee55762e23ed88923b9a41026dbf6900))
* adjust readme ([82d3957](https://github.com/redis-field-engineering/gha-clone-releases/commit/82d39571c2761bea062c15ccc5b01822d424e5f0))
* automated doc update ([6cc82f9](https://github.com/redis-field-engineering/gha-clone-releases/commit/6cc82f9c9d2110ac34ea510d4d926adce8ba9b7f))
* automated doc update ([a1b1ffa](https://github.com/redis-field-engineering/gha-clone-releases/commit/a1b1ffa326fa2dc5241d427e1f78287b86fac389))
* automated doc update ([0a96811](https://github.com/redis-field-engineering/gha-clone-releases/commit/0a96811c3ae1daaf016819b2454002237642b065))
* automated doc update ([b224d74](https://github.com/redis-field-engineering/gha-clone-releases/commit/b224d74e9168db5fc21dddf0a6216bad0c521846))
* automated doc update ([62a0920](https://github.com/redis-field-engineering/gha-clone-releases/commit/62a0920d8fb18b62d4b9ad54afb09dbf6b12d7fe))
* automated doc update ([4f09488](https://github.com/redis-field-engineering/gha-clone-releases/commit/4f0948832eb14039e24035040bf811bf2e6deca7))
* automated doc update ([5f6e331](https://github.com/redis-field-engineering/gha-clone-releases/commit/5f6e331a64fa69fa494b1698ed3bbb02ff1ef0a6))
* automated doc update ([eb82fcb](https://github.com/redis-field-engineering/gha-clone-releases/commit/eb82fcb84bd01bce846765794973b42a2db42e19))
* automated doc update ([fe30a95](https://github.com/redis-field-engineering/gha-clone-releases/commit/fe30a9548216042cc399ae1a270df3b96d1b21cf))
* automated doc update ([57ce5db](https://github.com/redis-field-engineering/gha-clone-releases/commit/57ce5db22d983bc9b1a928d432dd13964c79a761))
* automated doc update ([1742284](https://github.com/redis-field-engineering/gha-clone-releases/commit/1742284181f3f9335f56c8ff1542dadae7432525))
* automated doc update ([3f9bbef](https://github.com/redis-field-engineering/gha-clone-releases/commit/3f9bbefad07ffbc237074743994d819fea034c8f))
* update docs on GHE ([dc1b256](https://github.com/redis-field-engineering/gha-clone-releases/commit/dc1b256dc83f03234667f29c7bdb2eba03b3bde7))

## [1.9.0](https://github.com/andrewthetechie/gha-clone-releases/compare/v1.8.1...v1.9.0) (2024-02-11)


### Features

* support a separate token for destination  ([#185](https://github.com/andrewthetechie/gha-clone-releases/issues/185)) ([17454d6](https://github.com/andrewthetechie/gha-clone-releases/commit/17454d688fd0deeea68f7f07557c2b2eeefc13ca))

## [1.8.1](https://github.com/andrewthetechie/gha-clone-releases/compare/v1.8.0...v1.8.1) (2023-10-06)


### Bug Fixes

* pin to bullseye ([257aa64](https://github.com/andrewthetechie/gha-clone-releases/commit/257aa6487d6fe82375fa337e15dbed8ac3b77349))


### Documentation

* update docs on GHE ([dc1b256](https://github.com/andrewthetechie/gha-clone-releases/commit/dc1b256dc83f03234667f29c7bdb2eba03b3bde7))

## [1.8.0](https://github.com/andrewthetechie/gha-clone-releases/compare/v1.7.0...v1.8.0) (2023-05-21)


### Features

* support Github Enterprise ([#40](https://github.com/andrewthetechie/gha-clone-releases/issues/40)) ([3eb6682](https://github.com/andrewthetechie/gha-clone-releases/commit/3eb6682f982d9964af35d61ab43ecc46eaf579bf))


### Bug Fixes

* **poetry:** update poetry to 1.5.0 ([#39](https://github.com/andrewthetechie/gha-clone-releases/issues/39)) ([6726037](https://github.com/andrewthetechie/gha-clone-releases/commit/6726037a65529796f3abd944aef1406113924013))


### Documentation

* add jrbe228 as a contributor for bug, and ideas ([#31](https://github.com/andrewthetechie/gha-clone-releases/issues/31)) ([b0ab4ef](https://github.com/andrewthetechie/gha-clone-releases/commit/b0ab4ef2e5c6a86a4a276ca58ddf1628a0fdaf7e))
* automated doc update ([6cc82f9](https://github.com/andrewthetechie/gha-clone-releases/commit/6cc82f9c9d2110ac34ea510d4d926adce8ba9b7f))

## [1.7.0](https://github.com/andrewthetechie/gha-clone-releases/compare/v1.6.5...v1.7.0) (2023-05-16)


### Features

* support auth for asset download ([#29](https://github.com/andrewthetechie/gha-clone-releases/issues/29)) ([72e76fa](https://github.com/andrewthetechie/gha-clone-releases/commit/72e76fa103916de8a451af81b5dbd81594b5b213))

## [1.6.5](https://github.com/andrewthetechie/gha-clone-releases/compare/v1.6.4...v1.6.5) (2023-05-15)


### Bug Fixes

* fix debug output and sets ([fca3eab](https://github.com/andrewthetechie/gha-clone-releases/commit/fca3eab8f08f781262cb871b95681e9cde6c44e4))

## [1.6.4](https://github.com/andrewthetechie/gha-clone-releases/compare/v1.6.3...v1.6.4) (2023-05-15)


### Bug Fixes

* make debug text more useful ([fde2af9](https://github.com/andrewthetechie/gha-clone-releases/commit/fde2af950f908ef24b126fee195c6afe0d51a315))

## [1.6.3](https://github.com/andrewthetechie/gha-clone-releases/compare/v1.6.2...v1.6.3) (2023-05-15)


### Bug Fixes

* adjust debug text to be more useful ([2b79026](https://github.com/andrewthetechie/gha-clone-releases/commit/2b79026f3f4000fbf31c8c2824fa867f6fd65ed8))

## [1.6.2](https://github.com/andrewthetechie/gha-clone-releases/compare/v1.6.1...v1.6.2) (2023-05-15)


### Bug Fixes

* more debug info ([72e5057](https://github.com/andrewthetechie/gha-clone-releases/commit/72e5057da2e4d331ac73018374bcad64e0de1111))

## [1.6.1](https://github.com/andrewthetechie/gha-clone-releases/compare/v1.6.0...v1.6.1) (2023-05-15)


### Bug Fixes

* add more debugging output ([f089b81](https://github.com/andrewthetechie/gha-clone-releases/commit/f089b813bd82ce031013395c583ff11996502bec))


### Documentation

* add andrewthetechie as a contributor for code, doc, and 2 more ([#21](https://github.com/andrewthetechie/gha-clone-releases/issues/21)) ([78d29fb](https://github.com/andrewthetechie/gha-clone-releases/commit/78d29fb84dcbb3586e905e224729924064c05e84))
* automated doc update ([a1b1ffa](https://github.com/andrewthetechie/gha-clone-releases/commit/a1b1ffa326fa2dc5241d427e1f78287b86fac389))

## [1.6.0](https://github.com/andrewthetechie/gha-clone-releases/compare/v1.5.0...v1.6.0) (2023-05-13)


### Features

* copy draft release from src ([#17](https://github.com/andrewthetechie/gha-clone-releases/issues/17)) ([eb09597](https://github.com/andrewthetechie/gha-clone-releases/commit/eb09597f45cb93af436643846c3cf79a7b9edeb7))
* move to poetry ([#15](https://github.com/andrewthetechie/gha-clone-releases/issues/15)) ([1452522](https://github.com/andrewthetechie/gha-clone-releases/commit/1452522f0939990d4f180058886c8912ae5c75c9))
* support cloning assets to created releases ([#18](https://github.com/andrewthetechie/gha-clone-releases/issues/18)) ([11c658e](https://github.com/andrewthetechie/gha-clone-releases/commit/11c658e59405df8fd6bfece275b42a8b5d0e21f3))
