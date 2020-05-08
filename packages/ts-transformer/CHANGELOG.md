# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

## [2.0.2](https://github.com/formatjs/formatjs/compare/@formatjs/ts-transformer@2.0.1...@formatjs/ts-transformer@2.0.2) (2020-05-08)


### Bug Fixes

* **@formatjs/ts-transformer:** fix nested formatMessage case ([9d6592f](https://github.com/formatjs/formatjs/commit/9d6592f8269b1e17cc326e02a1675cbe0f47c41c))
* **@formatjs/ts-transformer:** rm _ from macro list ([92d5eaa](https://github.com/formatjs/formatjs/commit/92d5eaa4abaf614a186bc4add4c8551c5c729dcb))





## [2.0.1](https://github.com/formatjs/formatjs/compare/@formatjs/ts-transformer@2.0.0...@formatjs/ts-transformer@2.0.1) (2020-05-07)


### Bug Fixes

* **@formatjs/ts-transformer:** add extraction for defineMessage also ([c2a8a37](https://github.com/formatjs/formatjs/commit/c2a8a3765499b09c253895f02a452e3eaf9eddc0))





# [2.0.0](https://github.com/formatjs/formatjs/compare/@formatjs/ts-transformer@1.1.7...@formatjs/ts-transformer@2.0.0) (2020-05-07)


### Features

* **@formatjs/ts-transformer:** rm dependency on typechecker ([46a675f](https://github.com/formatjs/formatjs/commit/46a675f572017f2bffe7a42dcc0bf68a824aaf69))


### BREAKING CHANGES

* **@formatjs/ts-transformer:** Also remove `moduleSourceName` option
Dependency on typechecker means we cannot run w/ just `transpileModule`
Typechecking is also a lot slower





## [1.1.7](https://github.com/formatjs/formatjs/compare/@formatjs/ts-transformer@1.1.6...@formatjs/ts-transformer@1.1.7) (2020-05-06)


### Bug Fixes

* **@formatjs/ts-transformer:** expand extraction to `formatMessage()` as well ([146f1d3](https://github.com/formatjs/formatjs/commit/146f1d39fe0f42cba04dc25c391d03a5fbb39d28))





## 1.1.6 (2020-04-28)

**Note:** Version bump only for package @formatjs/ts-transformer





## [1.1.5](https://github.com/formatjs/formatjs/compare/@formatjs/ts-transformer@1.1.4...@formatjs/ts-transformer@1.1.5) (2020-04-25)

**Note:** Version bump only for package @formatjs/ts-transformer





## [1.1.4](https://github.com/formatjs/formatjs/compare/@formatjs/ts-transformer@1.1.3...@formatjs/ts-transformer@1.1.4) (2020-04-24)


### Bug Fixes

* **eslint-plugin-formatjs:** add missing dep ([776390e](https://github.com/formatjs/formatjs/commit/776390e9d6cb3bc1eef07b2e92057136cfe95b76))





## [1.1.3](https://github.com/formatjs/formatjs/compare/@formatjs/ts-transformer@1.1.2...@formatjs/ts-transformer@1.1.3) (2020-04-20)

**Note:** Version bump only for package @formatjs/ts-transformer





## [1.1.2](https://github.com/formatjs/formatjs/compare/@formatjs/ts-transformer@1.1.1...@formatjs/ts-transformer@1.1.2) (2020-04-16)


### Bug Fixes

* **@formatjs/ts-transformer:** fix id generation when description is falsy ([c6a862a](https://github.com/formatjs/formatjs/commit/c6a862adc3f378d1d21130a557e291292bca9d78))





## [1.1.1](https://github.com/formatjs/formatjs/compare/@formatjs/ts-transformer@1.1.0...@formatjs/ts-transformer@1.1.1) (2020-03-29)

**Note:** Version bump only for package @formatjs/ts-transformer





# [1.1.0](https://github.com/formatjs/formatjs/compare/@formatjs/ts-transformer@1.0.12...@formatjs/ts-transformer@1.1.0) (2020-03-22)


### Features

* **@formatjs/ts-transformer:** rm support for FormattedHTMLMessage ([ac592fa](https://github.com/formatjs/formatjs/commit/ac592fa90e5eb9e486462c7c75167879bb3ce86d))





## [1.0.12](https://github.com/formatjs/formatjs/compare/@formatjs/ts-transformer@1.0.11...@formatjs/ts-transformer@1.0.12) (2020-03-18)

**Note:** Version bump only for package @formatjs/ts-transformer





## [1.0.11](https://github.com/formatjs/formatjs/compare/@formatjs/ts-transformer@1.0.10...@formatjs/ts-transformer@1.0.11) (2019-11-26)


### Bug Fixes

* **@formatjs/ts-transformer:** use .text instead of .getText ([961a680](https://github.com/formatjs/formatjs/commit/961a680e687506db1fb81b682ef773fd6c538258))





## [1.0.10](https://github.com/formatjs/formatjs/compare/@formatjs/ts-transformer@1.0.9...@formatjs/ts-transformer@1.0.10) (2019-11-26)


### Bug Fixes

* **@formatjs/ts-transformer:** fix quote issue ([a9edba2](https://github.com/formatjs/formatjs/commit/a9edba2182ee0ffa6e6c6d482e6dcd9882eba9c0))





## [1.0.9](https://github.com/formatjs/formatjs/compare/@formatjs/ts-transformer@1.0.8...@formatjs/ts-transformer@1.0.9) (2019-11-25)

**Note:** Version bump only for package @formatjs/ts-transformer





## [1.0.8](https://github.com/formatjs/formatjs/compare/@formatjs/ts-transformer@1.0.7...@formatjs/ts-transformer@1.0.8) (2019-11-20)


### Bug Fixes

* **lint:** fix lint config and rerun ([041eb99](https://github.com/formatjs/formatjs/commit/041eb99706164048b5b8ce7079955897ce27ed70))





## [1.0.7](https://github.com/formatjs/formatjs/compare/@formatjs/ts-transformer@1.0.6...@formatjs/ts-transformer@1.0.7) (2019-11-10)


### Bug Fixes

* **intl-messageformat:** pass raw locales down to individual formatters ([3a74c2e](https://github.com/formatjs/formatjs/commit/3a74c2e7c6592de3a4f5ca182c5846fe095abe55)), closes [#255](https://github.com/formatjs/formatjs/issues/255)





## [1.0.6](https://github.com/formatjs/formatjs/compare/@formatjs/ts-transformer@1.0.5...@formatjs/ts-transformer@1.0.6) (2019-11-08)


### Bug Fixes

* **@formatjs/ts-transformer:** handle props.intl.formatMessage case ([afaa03d](https://github.com/formatjs/formatjs/commit/afaa03d3104145523c11ebe3ba85f92e560ee8a7))





## [1.0.5](https://github.com/formatjs/formatjs/compare/@formatjs/ts-transformer@1.0.4...@formatjs/ts-transformer@1.0.5) (2019-11-07)


### Bug Fixes

* **@formatjs/ts-transformer:** fix AST node manipulation ([1c9850e](https://github.com/formatjs/formatjs/commit/1c9850e4f21ad96c5096dafbf12081b3c6efd5c1))





## [1.0.4](https://github.com/formatjs/formatjs/compare/@formatjs/ts-transformer@1.0.3...@formatjs/ts-transformer@1.0.4) (2019-11-07)


### Bug Fixes

* **@formatjs/ts-transformer:** preserve multi arguments in formatMessage call ([3404c12](https://github.com/formatjs/formatjs/commit/3404c12aacc2bd75db8fd9a2213b0ef7c7ae95e7))





## [1.0.3](https://github.com/formatjs/formatjs/compare/@formatjs/ts-transformer@1.0.2...@formatjs/ts-transformer@1.0.3) (2019-11-06)


### Bug Fixes

* **@formatjs/ts-transformer:** fix overrideIdFn string case ([ad87c54](https://github.com/formatjs/formatjs/commit/ad87c5414601ba8d9f662c1c6d88f7ad2fb54031))





## [1.0.2](https://github.com/formatjs/formatjs/compare/@formatjs/ts-transformer@1.0.1...@formatjs/ts-transformer@1.0.2) (2019-11-06)


### Bug Fixes

* **@formatjs/ts-transformer:** handle case where we dont import hooks ([6afb5af](https://github.com/formatjs/formatjs/commit/6afb5af6ca1246327d36d06c4930dec21f8b0421))





## 1.0.1 (2019-11-05)

**Note:** Version bump only for package @formatjs/ts-transformer