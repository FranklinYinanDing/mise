# Changelog

## [2024.5.8](https://github.com/jdx/mise/compare/v2024.5.7..v2024.5.8) - 2024-05-12

### 🐛 Bug Fixes

- use correct url for aur-bin by [@jdx](https://github.com/jdx) in [a683c15](https://github.com/jdx/mise/commit/a683c1593d3c83660a42e4e6685522edb20e0480)
- handle race condition when initializing backends with dependencies by [@jdx](https://github.com/jdx) in [#2071](https://github.com/jdx/mise/pull/2071)

## [2024.5.7](https://github.com/jdx/mise/compare/v2024.5.6..v2024.5.7) - 2024-05-12

### 🧪 Testing

- add coverage report summary by [@jdx](https://github.com/jdx) in [#2065](https://github.com/jdx/mise/pull/2065)

### 🔍 Other Changes

- fix release job by [@jdx](https://github.com/jdx) in [a491270](https://github.com/jdx/mise/commit/a49127029b67d39f80708e47cfc20351faca941f)
- fix release job by [@jdx](https://github.com/jdx) in [90268db](https://github.com/jdx/mise/commit/90268dbdbb71f6e0ba51dbc657536029c2aac099)

## [2024.5.6](https://github.com/jdx/mise/compare/v2024.5.5..v2024.5.6) - 2024-05-12

### 🚀 Features

- add cargo-binstall as dependency for cargo backend by [@jdx](https://github.com/jdx) in [94868af](https://github.com/jdx/mise/commit/94868afcca9731c43fb48670ed0d7d4f40a4fab8)

### 🐛 Bug Fixes

- performance fix for _.file/_.path by [@jdx](https://github.com/jdx) in [76202de](https://github.com/jdx/mise/commit/76202ded1bb47ecf9c1a5a7e6f71216aca26c68e)

### 🚜 Refactor

- **(cargo)** improve cargo-binstall check by [@jdx](https://github.com/jdx) in [d1432e0](https://github.com/jdx/mise/commit/d1432e0316a1e1b335022372ef0896c5b5b7b0df)

### 🧪 Testing

- **(e2e)** fix mise path by [@jdx](https://github.com/jdx) in [f6de41a](https://github.com/jdx/mise/commit/f6de41af71e7ad03d831bf602c291f38dd6c0fd8)
- isolation of end-to-end tests by [@Adirelle](https://github.com/Adirelle) in [#2047](https://github.com/jdx/mise/pull/2047)
- simplify release e2e jobs by [@jdx](https://github.com/jdx) in [b97a0bb](https://github.com/jdx/mise/commit/b97a0bb563762a4de40ea49a5bccb3a74daafb8f)

### 🔍 Other Changes

- **(aur)** added usage as optional dependency by [@jdx](https://github.com/jdx) in [5280ece](https://github.com/jdx/mise/commit/5280ece4f2f2337e7dd56c17062a09fdf1e1c808)
- **(codacy)** fix codacy on forks by [@jdx](https://github.com/jdx) in [c70d567](https://github.com/jdx/mise/commit/c70d567b2529e7054a79e461114a85c2fceb457d)
- switch back to secret for codacy by [@jdx](https://github.com/jdx) in [7622cfb](https://github.com/jdx/mise/commit/7622cfbb969c9a40638855d13009a72e4dc91ac8)
- added semantic-pr check by [@jdx](https://github.com/jdx) in [#2063](https://github.com/jdx/mise/pull/2063)
- fix whitespace by [@jdx](https://github.com/jdx) in [3eadcb5](https://github.com/jdx/mise/commit/3eadcb548960729e7168842af18c8200b3b70863)

## [2024.5.5](https://github.com/jdx/mise/compare/v2024.5.4..v2024.5.5) - 2024-05-12

### 🐛 Bug Fixes

- **(pipx)** remove unneeded unwrap by [@jdx](https://github.com/jdx) in [273c73d](https://github.com/jdx/mise/commit/273c73d15d77d42e8ff4ed732335cc418f903e0b)
- resolve bug with backends not resolving mise-installed tools by [@jdx](https://github.com/jdx) in [#2059](https://github.com/jdx/mise/pull/2059)

## [2024.5.4] - 2024-05-11

### 🚀 Features

- add more directory env var configs by [@jdx](https://github.com/jdx) in [#2056](https://github.com/jdx/mise/pull/2056)

### 🚜 Refactor

- move opts from ToolVersion to ToolVersionRequest struct by [@jdx](https://github.com/jdx) in [#2057](https://github.com/jdx/mise/pull/2057)
- remove use of mutex by [@jdx](https://github.com/jdx) in [278d028](https://github.com/jdx/mise/commit/278d028247adcd3a166f11281f81dd7a437e5547)

### 📚 Documentation

- **(changelog)** cleaning up changelog by [@jdx](https://github.com/jdx) in [845c1af](https://github.com/jdx/mise/commit/845c1afdc58437d083f0f3d50e4733142bef2281)

### 🔍 Other Changes

- Commit from GitHub Actions (test) by [@mise-en-dev](https://github.com/mise-en-dev) in [695f851](https://github.com/jdx/mise/commit/695f8513c0117623ca190c052c603a6b910814ad)
- Merge pull request #2019 from jdx/release by [@jdx](https://github.com/jdx) in [6bbd3d1](https://github.com/jdx/mise/commit/6bbd3d17d353eba1684eb11799f6b3684e38b578)
- include symlink error context in error message by [@KlotzAndrew](https://github.com/KlotzAndrew) in [ddd58fc](https://github.com/jdx/mise/commit/ddd58fc7eca72163dd0541596c5b6f06712aec28)
- Merge pull request #2040 from KlotzAndrew/aklotz/show_symlink_error by [@jdx](https://github.com/jdx) in [e71a8a0](https://github.com/jdx/mise/commit/e71a8a07e3385bf9bfe0985259325febd3bcf977)
- continue git subtree on error by [@jdx](https://github.com/jdx) in [a2c590c](https://github.com/jdx/mise/commit/a2c590c7dd82ac60c22844ef7e4ef88da3c1e507)
- squash registry by [@jdx](https://github.com/jdx) in [143ea6e](https://github.com/jdx/mise/commit/143ea6e589c8232c1d8a61aa33a576815754a3f0)
- reclone registry in release-plz job by [@jdx](https://github.com/jdx) in [05848a5](https://github.com/jdx/mise/commit/05848a52ea19c27e77ebf30310e7a4753c1b8ab0)
- reclone registry in release-plz job by [@jdx](https://github.com/jdx) in [c020c1e](https://github.com/jdx/mise/commit/c020c1e60347fcf9538293d141922eff1728500a)
- updated changelog by [@jdx](https://github.com/jdx) in [0465520](https://github.com/jdx/mise/commit/0465520f4c2d1d78a5ddc0c1d955a062d6f34d3b)
- show bash trace in release-plz by [@jdx](https://github.com/jdx) in [8a322bc](https://github.com/jdx/mise/commit/8a322bc2740a1c5676574cebdeb4c02726f36358)

### New Contributors

* @KlotzAndrew made their first contribution

<!-- generated by git-cliff -->
