# Changelog

<a name="3.0.0"></a>
## 3.0.0 (2020-07-03)

### Added

- ✨ Add the possibility to create multiple image in one call ([#38](https://github.com/frinyvonnick/node-html-to-image/issues/38)) [[fed3ee5](https://github.com/frinyvonnick/node-html-to-image/commit/fed3ee500edacf5c4af00624009978fdd41b5c2b)]

### Breaking changes

- 💥 Set waitUntil default value to networkidle0 [[1436613](https://github.com/frinyvonnick/node-html-to-image/commit/1436613532f32ea01231112d802a9e041f5af7c4)]

### Fixed

- 🐛 Pass waitUntil option to setContent method ([#40](https://github.com/frinyvonnick/node-html-to-image/issues/40)) [[ad69d33](https://github.com/frinyvonnick/node-html-to-image/commit/ad69d337f0fcd2726b3930972576eabcd328bcdb)]
- ✏️ Fix typo in example ([#29](https://github.com/frinyvonnick/node-html-to-image/issues/29)) [[459f573](https://github.com/frinyvonnick/node-html-to-image/commit/459f573001c94ebfe85b87121197262f88689af0)]

### Miscellaneous

- 📝 Add a synopsis in the usage section ([#41](https://github.com/frinyvonnick/node-html-to-image/issues/41)) [[c92d252](https://github.com/frinyvonnick/node-html-to-image/commit/c92d25265d0a623b7bba7a8b3e3a590d3c1dcfed)]


<a name="2.1.1"></a>
## 2.1.1 (2020-05-20)

### Removed

- 🔥 Remove npm lockfile [[8a1b22f](https://github.com/frinyvonnick/node-html-to-image/commit/8a1b22fb85bc14bc53045f860dd5df57247353bb)]

### Fixed

- 🐛 Fix issue related to default quality property with png type ([#28](https://github.com/frinyvonnick/node-html-to-image/issues/28)) [[cddf200](https://github.com/frinyvonnick/node-html-to-image/commit/cddf200dadf85eec6ff23a349ba5793187bc16f3)]
- ✏️ Remove extra style tag in example ([#26](https://github.com/frinyvonnick/node-html-to-image/issues/26)) [[06f16e7](https://github.com/frinyvonnick/node-html-to-image/commit/06f16e791eb026460c11394387cab95aee3ba144)]


<a name="2.1.0"></a>
## 2.1.0 (2020-05-19)

### Added

- ✨ Add the quality parameter for jpg images ([#22](https://github.com/frinyvonnick/node-html-to-image/issues/22)) [[a4069e5](https://github.com/frinyvonnick/node-html-to-image/commit/a4069e544310f7a2c4d80a103989e753230567f3)]

### Changed

- 📌 Move gitmoji-changelog to dev dependencies ([#25](https://github.com/frinyvonnick/node-html-to-image/issues/25)) [[acfd889](https://github.com/frinyvonnick/node-html-to-image/commit/acfd889aa4761c7bedb9ee9b6e5fb9ffc0ef06d1)]


<a name="2.0.0"></a>
## 2.0.0 (2020-05-11)

### Added

- ✨ Add encoding option to allow user to change default encoding ([#11](https://github.com/frinyvonnick/node-html-to-image/issues/11)) [[8dacb45](https://github.com/frinyvonnick/node-html-to-image/commit/8dacb452c563df2b97e09294d55b155cc0150734)]
- ✨ Return the buffer from .screenshot() in case we don&#x27;t want to save image ([#10](https://github.com/frinyvonnick/node-html-to-image/issues/10)) [[22d5085](https://github.com/frinyvonnick/node-html-to-image/commit/22d5085c59ca1be25e6ff712e06da430a7669066)]

### Changed

- ⬆️ Bump acorn from 5.7.3 to 5.7.4 ([#7](https://github.com/frinyvonnick/node-html-to-image/issues/7)) [[22746df](https://github.com/frinyvonnick/node-html-to-image/commit/22746df0befaf6f00f0a96225f07160f97329831)]

### Breaking changes

- 💥 Remove output requirement ([#16](https://github.com/frinyvonnick/node-html-to-image/issues/16)) [[3c11b84](https://github.com/frinyvonnick/node-html-to-image/commit/3c11b84a36d861251a798c98f8692757126d9f0e)]

### Removed

- 🔥 Remove deprecated explanations in Run tests section [[bec08d6](https://github.com/frinyvonnick/node-html-to-image/commit/bec08d6ec467362e42f428c2db7eda960210e926)]

### Fixed

- ✏️ Fix typo in properties table ([#15](https://github.com/frinyvonnick/node-html-to-image/issues/15)) [[df746df](https://github.com/frinyvonnick/node-html-to-image/commit/df746df38be782c348dd10dce83b55c0d2d85353)]

### Miscellaneous

- 📝 Update documentation to make output optional [[d4dcf1e](https://github.com/frinyvonnick/node-html-to-image/commit/d4dcf1e720737445f5e10dc62346e591d4e3d636)]
- 💡 Improve dealing with local images instructions ([#8](https://github.com/frinyvonnick/node-html-to-image/issues/8)) [[c73a79a](https://github.com/frinyvonnick/node-html-to-image/commit/c73a79a6cba7d9ef6ba815f93772b078fe8c3ae8)]


<a name="1.2.0"></a>
## 1.2.0 (2020-03-24)

### Added

- ✨ Add transparent option to omit background ([#6](https://github.com/frinyvonnick/node-html-to-image/issues/6)) [[a63f0f2](https://github.com/frinyvonnick/node-html-to-image/commit/a63f0f2ce18f1a12e47f1dfa52765e905e175a9c)]

### Changed

- ♻️ Use Tesseract.js to simplify installation [[afa5f46](https://github.com/frinyvonnick/node-html-to-image/commit/afa5f4645e75c8ca2d8fc50284de057381422022)]

### Miscellaneous

- 📝 Add a section about dealing with images [[07cb135](https://github.com/frinyvonnick/node-html-to-image/commit/07cb135b2aab78d82370e5a417678fba4a2d3446)]
- 📝 Add a section about output image resolution [[7ea6de7](https://github.com/frinyvonnick/node-html-to-image/commit/7ea6de72aa5df8d2ed26902fb8a8a60870d5af85)]


<a name="1.1.0"></a>
## 1.1.0 (2019-12-06)

### Added

- ✨ Add waitUntil option [[a8f1b46](https://github.com/frinyvonnick/node-html-to-image/commit/a8f1b46c7ab702553f66c3d6a26adec6b7f05a8c)]

### Miscellaneous

- 📝 Add a mention to the cli [[bebd0f6](https://github.com/frinyvonnick/node-html-to-image/commit/bebd0f6211fcacca307949670d0eb9f4954f7e46)]
- 📝 Fix examples [[2b1879b](https://github.com/frinyvonnick/node-html-to-image/commit/2b1879b796d61873be6957c37e7aab084c045112)]


<a name="1.0.0"></a>
## 1.0.0 (2019-12-05)

### Added

- ✨ Implement a function that generates an image from html ([#1](https://github.com/frinyvonnick/node-html-to-image/issues/1)) [[2de2304](https://github.com/frinyvonnick/node-html-to-image/commit/2de23044e18fda2e1bcb4681be9555c078cce421)]

### Miscellaneous

- 📝 Improve examples and add information about handlebars [[b4d2274](https://github.com/frinyvonnick/node-html-to-image/commit/b4d22742ab07169a7ded87b084493479bbbc32c0)]
- 📝 Change emoji in title [[2ea3e7c](https://github.com/frinyvonnick/node-html-to-image/commit/2ea3e7cf3c89e3c491b554fbf729279c4946c794)]
- 📝 Add missing comma in handlebars example [[2dc3924](https://github.com/frinyvonnick/node-html-to-image/commit/2dc39247d3ce80b8df1b5b737506e42ca5bf05cf)]
-  Initial commit [[d75796d](https://github.com/frinyvonnick/node-html-to-image/commit/d75796d6e9908eedff32484eb416f56e92a0a6fe)]


