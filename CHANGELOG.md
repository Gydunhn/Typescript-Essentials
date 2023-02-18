# Change Log

All notable changes to the Typescript Essentials - Extension Pack for Visual Studio Code will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

# [Unreleased]

### Added

* Setting.json configs files.
* TSLint Documentation.

### Removed

* Find unused exports, Removed because it conflicts with the extension host, restarts it over and over again until it breaks.

## [1.0.2] - 2023-02-01

### Added

* Find unused exports, A Visual Studio Code extension for displaying all unused exports in a typescript/javascript project.

## [1.0.1] - 2023-02-01

### Changed

* ReadMe Badges

## [1.0.0] - 2022-10-14

This will be an important change in how this extension pack works, so as not to have imports of other duplicate extensions, therefore the installation of this one will be more efficient.

### Added

* Javascript-Essentials, which already includes:  
  * npm Intellisense.
  * Visual Studio IntelliCode.
  * JavaScript (ES6) code snippets.
  * Debugger for Firefox.

### Removed

* npm Intellisense.
* Visual Studio IntelliCode.
* JavaScript (ES6) code snippets.
* Debugger for Firefox.

## [0.2.3] - 2022-10-14

### Removed

* TSLint, has been deprecated in favor of ESLint and this extension has also been deprecated in favor of ESLint's tooling.
* npm, has been deprecated. Support for running npm scripts is now provided by VS Code. You can run npm scripts as tasks using task auto detection or from the npm scripts explorer.

## [0.2.2] - 2020-10-06

### Changed

* Compatibility with vsCode 1.35.0 x32

## [0.2.1] - 2020-08-28

### Changed

* the KeyWords were modified

## [0.2.0] - 2020-04-29

### Added

* npm egamma Extension

## [0.1.1] - 2020-04-29

### Fixed

* Change Log Tags Links

## [0.1.0] - 2020-04-27

### Added

* npm Intellisense Extension
* Visual Studio IntelliCode Extension
* JavaScript (ES6) code snippets

## [0.0.1] - 2020-04-27

### Added

* Initial release
  * Created extension pack

[Unreleased]: https://github.com/Gydunhn/Typescript-Essentials/tree/develop
[1.0.2]: https://github.com/Gydunhn/Typescript-Essentials/releases/tag/1.0.2
[1.0.1]: https://github.com/Gydunhn/Typescript-Essentials/releases/tag/1.0.1
[1.0.0]: https://github.com/Gydunhn/Typescript-Essentials/releases/tag/1.0.0
[0.2.3]: https://github.com/Gydunhn/Typescript-Essentials/releases/tag/0.2.3
[0.2.2]: https://github.com/Gydunhn/Typescript-Essentials/releases/tag/0.2.2
[0.2.1]: https://github.com/Gydunhn/Typescript-Essentials/releases/tag/0.2.1
[0.2.0]: https://github.com/Gydunhn/Typescript-Essentials/releases/tag/0.2.0
[0.1.1]: https://github.com/Gydunhn/Typescript-Essentials/releases/tag/0.1.1
[0.1.0]: https://github.com/Gydunhn/Typescript-Essentials/releases/tag/0.1.0
[0.0.1]: https://github.com/Gydunhn/Typescript-Essentials/releases/tag/0.0.1
