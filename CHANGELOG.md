# Perjury change log

Perjury adheres to [Semantic Versioning 2.0.0](https://semver.org/spec/v2.0.0.html).

## 1.1.4 - 2018-04-27

### Fixed

* Fix `package-lock.json` being incorrect

## 1.1.3 - 2018-04-27

### Changed

* Remove Coveralls support since this module is just an alias now
* Run tests on Node 10

## 1.1.2 - 2018-04-27

### Changed

* This module is now an alias for `vows@^1.0.0-alpha.1`, which is based on the Perjury codebase instead of the (old, legacy) Vows codebase - see the Vows changelog for change from `perjury@1.1.1`

## 1.1.1 - 2018-02-01

### Changed

* Run tests on Node 9
* Update dependencies (in particular: move from `coffee-script` to `coffeescript`)

## 1.1.0 - 2017-11-06

### Changed

* Explicitly allow calling `this.callback()` synchronously in topic

## 1.0.12

### Fixed

* Resolve Node 4 crashes due to ES6 spread/rest/destructuring u	se

## 1.0.11 - 2017-11-06

### Changed

* Improve `atMostOnce()` behavior to have a more specific error and provide debugging output

### Fixed

* Resolve many linter errors

## 1.0.10 - 2017-11-02

### Fixed

* Resolve Node 4 crashes due to ES6 rest parameter use

## 1.0.9 - 2017-11-01

### Changed

* Switch from JSHint to ESLint and fix ESLint errors

## 1.0.8 - 2017-11-01

### Added

* Test that the report shows the right number of errors

## 1.0.7 - 2017-11-01

### Fixed

* Add a missing `'use strict';` statement

## 1.0.6 - 2017-11-01

### Changed

* Test results are now indented

## 1.0.5 - 2017-11-01

### Fixed

* Update package-lock.json

## 1.0.4 - 2017-11-01

### Added

* Add engine version compatibility in package.json

### Fixed

* Correctly display batch output near the batch title
* Fix typo in compatibility notes

## 1.0.3 - 2017-10-25

### Added

* Document using async/await in topic and teardown

## 1.0.2 - 2017-10-25

### Added

* Expand test suite coverage

## 1.0.1 - 2017-10-25

### Fixed

* Fix typo in compatibility notes

## 1.0.0 - 2017-10-25

### Added

* Document compatibility notes in README
* Expand test suite coverage
* Node 8 is now supported

### Changed

* Upgrade dependencies

### Fixed

* Fix some typos in the README's examples
* Calling plain `perjury.assert()` instead of `perjury.assert.ok()` now actually works properly

### Breaking

* If you return a Promise from a topic or a teardown, that Promise is now resolved before passing it anywhere else

## 0.4.3 - 2017-02-10

### Added

* Expand test suite coverage

## 0.4.2 - 2016-10-07

No changes from 0.4.1.

## 0.4.1 - 2016-10-07

### Changed

* Improve internal test suite behavior

## 0.4.0 - 2016-10-07

TODO

## 0.3.5 - 2016-08-31

TODO

## 0.3.4 - 2016-08-31

TODO

## 0.3.3 - 2016-08-27

TODO

## 0.3.2 - 2016-08-26

TODO

## 0.3.1 - 2016-08-26

TODO

## 0.3.0 - 2016-08-25

TODO

## 0.2.2 - 2016-08-25

TODO

## 0.2.1 - 2016-08-25

TODO

## 0.2.0 - 2016-08-25

### Added

* Initial release
