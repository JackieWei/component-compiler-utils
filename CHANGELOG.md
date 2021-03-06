<a name="2.0.0"></a>
# [2.0.0](https://github.com/vuejs/component-compiler-utils/compare/v1.3.1...v2.0.0) (2018-06-03)


### Features

* Add async style compilation support ([#13](https://github.com/vuejs/component-compiler-utils/issues/13)) ([54464d6](https://github.com/vuejs/component-compiler-utils/commit/54464d6))
* allow/require compiler to be passed in for `parse` ([caa1538](https://github.com/vuejs/component-compiler-utils/commit/caa1538))


### BREAKING CHANGES

* vue template compiler must now be passed to `parse`
via options.



<a name="1.3.1"></a>
## [1.3.1](https://github.com/vuejs/component-compiler-utils/compare/v1.3.0...v1.3.1) (2018-05-28)


### Bug Fixes

* default parser was removed from prettier ([#15](https://github.com/vuejs/component-compiler-utils/issues/15)) ([598224d](https://github.com/vuejs/component-compiler-utils/commit/598224d))



<a name="1.3.0"></a>
# [1.3.0](https://github.com/vuejs/component-compiler-utils/compare/v1.2.1...v1.3.0) (2018-05-22)


### Features

* include href for <image> in transformAssetUrls (close [#12](https://github.com/vuejs/component-compiler-utils/issues/12)) ([86fddc2](https://github.com/vuejs/component-compiler-utils/commit/86fddc2))
* Provide installation instructions on missing language preprocessors ([#10](https://github.com/vuejs/component-compiler-utils/issues/10)) ([97e772c](https://github.com/vuejs/component-compiler-utils/commit/97e772c))



<a name="1.2.1"></a>
## [1.2.1](https://github.com/vuejs/component-compiler-utils/compare/v1.2.0...v1.2.1) (2018-04-26)


### Bug Fixes

* postcss import ([c845a80](https://github.com/vuejs/component-compiler-utils/commit/c845a80))



<a name="1.2.0"></a>
# [1.2.0](https://github.com/vuejs/component-compiler-utils/compare/v1.1.0...v1.2.0) (2018-04-26)


### Bug Fixes

* compile only lib directory ([#6](https://github.com/vuejs/component-compiler-utils/issues/6)) ([4f787b3](https://github.com/vuejs/component-compiler-utils/commit/4f787b3))


### Features

* accept postcss options and plugins ([#7](https://github.com/vuejs/component-compiler-utils/issues/7)) ([1456e3d](https://github.com/vuejs/component-compiler-utils/commit/1456e3d))



<a name="1.1.0"></a>
# [1.1.0](https://github.com/vuejs/component-compiler-utils/compare/9204f16...v1.1.0) (2018-04-24)


### Bug Fixes

* use more strict regex for matching css animation rules ([4644727](https://github.com/vuejs/component-compiler-utils/commit/4644727))


### Features

* adds stylus & less preprocessor ([#5](https://github.com/vuejs/component-compiler-utils/issues/5)) ([f2fd8b9](https://github.com/vuejs/component-compiler-utils/commit/f2fd8b9))
* preprocess scss/sass styles with node-sass ([#4](https://github.com/vuejs/component-compiler-utils/issues/4)) ([9204f16](https://github.com/vuejs/component-compiler-utils/commit/9204f16))



