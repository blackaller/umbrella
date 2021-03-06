# Change Log

All notable changes to this project will be documented in this file.
See [Conventional Commits](https://conventionalcommits.org) for commit guidelines.

<a name="1.2.0"></a>
# [1.2.0](https://github.com/thi-ng/umbrella/compare/@thi.ng/transducers@1.1.0...@thi.ng/transducers@1.2.0) (2018-02-18)


### Bug Fixes

* **transducers:** update imports `step()` ([48f8bb8](https://github.com/thi-ng/umbrella/commit/48f8bb8))


### Features

* **transducers:** add convolve2d xform & types ([ab8a855](https://github.com/thi-ng/umbrella/commit/ab8a855))
* **transducers:** add movingMedian() xform ([d7b1d0d](https://github.com/thi-ng/umbrella/commit/d7b1d0d))
* **transducers:** add range2d / range3d generators ([722042b](https://github.com/thi-ng/umbrella/commit/722042b))




<a name="1.1.0"></a>
# [1.1.0](https://github.com/thi-ng/umbrella/compare/@thi.ng/transducers@1.0.7...@thi.ng/transducers@1.1.0) (2018-02-08)


### Features

* **transducers:** add page() xform, update readme ([855d803](https://github.com/thi-ng/umbrella/commit/855d803))




<a name="1.0.7"></a>
## [1.0.7](https://github.com/thi-ng/umbrella/compare/@thi.ng/transducers@1.0.6...@thi.ng/transducers@1.0.7) (2018-02-02)




**Note:** Version bump only for package @thi.ng/transducers

<a name="1.0.6"></a>
## [1.0.6](https://github.com/thi-ng/umbrella/compare/@thi.ng/transducers@1.0.5...@thi.ng/transducers@1.0.6) (2018-02-01)


### Bug Fixes

* **transducers:** update comp() for typescript 2.7.* ([febe39f](https://github.com/thi-ng/umbrella/commit/febe39f))




<a name="1.0.5"></a>
## [1.0.5](https://github.com/thi-ng/umbrella/compare/@thi.ng/transducers@1.0.4...@thi.ng/transducers@1.0.5) (2018-01-31)




**Note:** Version bump only for package @thi.ng/transducers

<a name="1.0.4"></a>
## [1.0.4](https://github.com/thi-ng/umbrella/compare/@thi.ng/transducers@1.0.3...@thi.ng/transducers@1.0.4) (2018-01-30)




**Note:** Version bump only for package @thi.ng/transducers

<a name="1.0.3"></a>
## [1.0.3](https://github.com/thi-ng/umbrella/compare/@thi.ng/transducers@1.0.2...@thi.ng/transducers@1.0.3) (2018-01-29)




**Note:** Version bump only for package @thi.ng/transducers

<a name="1.0.2"></a>
## [1.0.2](https://github.com/thi-ng/umbrella/compare/@thi.ng/transducers@1.0.1...@thi.ng/transducers@1.0.2) (2018-01-29)


### Performance Improvements

* **transducers:** avoid result object cloning in struct() xform ([d774e32](https://github.com/thi-ng/umbrella/commit/d774e32))




<a name="1.0.1"></a>
## [1.0.1](https://github.com/thi-ng/umbrella/compare/@thi.ng/transducers@1.0.0...@thi.ng/transducers@1.0.1) (2018-01-29)




**Note:** Version bump only for package @thi.ng/transducers

<a name="1.0.0"></a>
# [1.0.0](https://github.com/thi-ng/umbrella/compare/@thi.ng/transducers@0.11.2...@thi.ng/transducers@1.0.0) (2018-01-28)


### Bug Fixes

* **transducers:** add "complete" step handling in scan() ([8e5204d](https://github.com/thi-ng/umbrella/commit/8e5204d))
* **transducers:** scan() complete handling ([44db970](https://github.com/thi-ng/umbrella/commit/44db970))


### Code Refactoring

* **transducers:** rename join() => str() rfn ([e268e35](https://github.com/thi-ng/umbrella/commit/e268e35))


### Features

* **transducers:** add every(), some() rfns ([63344e4](https://github.com/thi-ng/umbrella/commit/63344e4))
* **transducers:** add labeled() xform ([0b3c786](https://github.com/thi-ng/umbrella/commit/0b3c786))
* **transducers:** add multiplex() xform & docs ([beb2cee](https://github.com/thi-ng/umbrella/commit/beb2cee))
* **transducers:** add multiplexObj() ([931b67f](https://github.com/thi-ng/umbrella/commit/931b67f))
* **transducers:** add noop() xform, update readme ([7b21aa6](https://github.com/thi-ng/umbrella/commit/7b21aa6))
* **transducers:** add utf8Encode()/utf8Decode() xforms ([e50fa26](https://github.com/thi-ng/umbrella/commit/e50fa26))
* **transducers:** update frequencies() & groupByMap() ([4b8d037](https://github.com/thi-ng/umbrella/commit/4b8d037))
* **transducers:** update re-exports, extract throttleTime() into own file ([45d6bc6](https://github.com/thi-ng/umbrella/commit/45d6bc6))
* **transducers:** update re-exports, minor update reductions() ([e555ff5](https://github.com/thi-ng/umbrella/commit/e555ff5))
* **transducers:** update step() to support multiple results ([1f32fc0](https://github.com/thi-ng/umbrella/commit/1f32fc0))
* **transducers:** update throttle(), refactor take/dropNth ([e1a282c](https://github.com/thi-ng/umbrella/commit/e1a282c))


### BREAKING CHANGES

* **transducers:** throttle() requires stateful predicate now
* **transducers:** rename join() => str() reduer in prep for actual set join() op
* **transducers:** now possibly returns array instead of single value if wrapped transducer produced multiple results
