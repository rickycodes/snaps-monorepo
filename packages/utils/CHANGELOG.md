# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.22.4]
### Changed
- Add snap cronjobs ([#651](https://github.com/MetaMask/snaps-monorepo/pull/651))
- Improve keyring endowment error messaging ([#884](https://github.com/MetaMask/snaps-monorepo/pull/884))
- BREAKING: Replace Buffer with Typed Arrays ([#878](https://github.com/MetaMask/snaps-monorepo/pull/878))
- Stop including source code in state ([#861](https://github.com/MetaMask/snaps-monorepo/pull/861))
- Remove JSON schemas in favour of structs ([#862](https://github.com/MetaMask/snaps-monorepo/pull/862))
- 0.22.3 ([#856](https://github.com/MetaMask/snaps-monorepo/pull/856))
- 0.22.2 ([#841](https://github.com/MetaMask/snaps-monorepo/pull/841))
- Rename repository ([#842](https://github.com/MetaMask/snaps-monorepo/pull/842))
- 0.22.1 ([#824](https://github.com/MetaMask/snaps-monorepo/pull/824))
- 0.22.0 ([#810](https://github.com/MetaMask/snaps-monorepo/pull/810))
- Bump `@metamask/utils` to `3.1.0` ([#781](https://github.com/MetaMask/snaps-monorepo/pull/781))
- Add Snap Keyring support to execution environment ([#728](https://github.com/MetaMask/snaps-monorepo/pull/728))
- Merge test utils and simplify controller tests ([#782](https://github.com/MetaMask/snaps-monorepo/pull/782))
- Bump Jest to the latest version in all packages ([#750](https://github.com/MetaMask/snaps-monorepo/pull/750))
- 0.21.0 ([#776](https://github.com/MetaMask/snaps-monorepo/pull/776))
- Stop including `installing` snaps in `wallet_getSnaps` ([#765](https://github.com/MetaMask/snaps-monorepo/pull/765))
- Export test utils from utils package ([#743](https://github.com/MetaMask/snaps-monorepo/pull/743))
- 0.20.0 ([#711](https://github.com/MetaMask/snaps-monorepo/pull/711))
- 0.19.1 ([#698](https://github.com/MetaMask/snaps-monorepo/pull/698))
- 0.19.0 ([#687](https://github.com/MetaMask/snaps-monorepo/pull/687))
- Moved SnapController to xstate ([#676](https://github.com/MetaMask/snaps-monorepo/pull/676))
- Dedupe yarn.lock ([#617](https://github.com/MetaMask/snaps-monorepo/pull/617))
- BREAKING: Replace RegEx-based bundle processing and comment stripping with an AST-based solution ([#583](https://github.com/MetaMask/snaps-monorepo/pull/583))
- 0.18.1 ([#640](https://github.com/MetaMask/snaps-monorepo/pull/640))
- 0.18.0 ([#634](https://github.com/MetaMask/snaps-monorepo/pull/634))
- 0.17.0 ([#625](https://github.com/MetaMask/snaps-monorepo/pull/625))
- @metamask/eslint config@9.0.0 ([#559](https://github.com/MetaMask/snaps-monorepo/pull/559))
- Rename package `publish` command to `publish:package` ([#547](https://github.com/MetaMask/snaps-monorepo/pull/547))
- 0.16.0 ([#540](https://github.com/MetaMask/snaps-monorepo/pull/540))
- Fix various monorepo / workspace issues ([#496](https://github.com/MetaMask/snaps-monorepo/pull/496))
- 0.15.0 ([#492](https://github.com/MetaMask/snaps-monorepo/pull/492))
- Update @metamask/auto-changelog to 2.6.0 ([#470](https://github.com/MetaMask/snaps-monorepo/pull/470))
- Fix yarn clean / build:clean not working on yarn 3 ([#469](https://github.com/MetaMask/snaps-monorepo/pull/469))
- Fix `jest-it-up` after Yarn 3 upgrade ([#467](https://github.com/MetaMask/snaps-monorepo/pull/467))
- Upgrade Yarn to v3 ([#463](https://github.com/MetaMask/snaps-monorepo/pull/463))
- 0.14.0 ([#454](https://github.com/MetaMask/snaps-monorepo/pull/454))
- 0.13.0 ([#447](https://github.com/MetaMask/snaps-monorepo/pull/447))
- 0.12.0 ([#425](https://github.com/MetaMask/snaps-monorepo/pull/425))

## [0.22.3]
### Fixed
- Make @babel/types a regular dependency ([#852](https://github.com/MetaMask/snaps-monorepo/pull/852))

## [0.22.2]
### Changed
- No changes this release.

## [0.22.1]
### Fixed
- Add browser entry point for `snap-utils` ([#820](https://github.com/MetaMask/snaps-monorepo/pull/820))

## [0.22.0]
### Added
- Add functionality required for Snap Keyring support ([#700](https://github.com/MetaMask/snaps-monorepo/pull/700), [#777](https://github.com/MetaMask/snaps-monorepo/pull/777))

## [0.21.0]
### Changed
- Run eval and fix manifest in bundler plugins ([#731](https://github.com/MetaMask/snaps-monorepo/pull/731))

## [0.20.0]
### Added
- **BREAKING:** Add Transaction Insight API ([#642](https://github.com/MetaMask/snaps-monorepo/pull/642))
- Add internal types from `@metamask/snap-types` ([#695](https://github.com/MetaMask/snaps-monorepo/pull/695))

### Changed
- **BREAKING:** Simplify manifest format for permission caveats ([#705](https://github.com/MetaMask/snaps-monorepo/pull/705))
- Reduce TypeScript compilation target for `snap-controllers` ([#708](https://github.com/MetaMask/snaps-monorepo/pull/708))

## [0.19.1]
### Added
- Generate source maps from modified code ([#615](https://github.com/MetaMask/snaps-monorepo/pull/615))

## [0.19.0]
### Changed
- Move eval functionality to utils package ([#666](https://github.com/MetaMask/snaps-monorepo/pull/666))
- Move manifest handling functionality to utils ([#652](https://github.com/MetaMask/snaps-monorepo/pull/652))
- Move JSON schemas and controller utils to utils package ([#623](https://github.com/MetaMask/snaps-monorepo/pull/623))

### Fixed
- Fixed missing AbortSignal in default endowments ([#682](https://github.com/MetaMask/snaps-monorepo/pull/682))

## [0.18.1]
### Changed
- No changes this release.

## [0.18.0]
### Changed
- Reduce TypeScript compilation target to ES2017 ([#628](https://github.com/MetaMask/snaps-monorepo/pull/628))

## [0.17.0]
### Changed
- **BREAKING:** Bump minimum Node version to 16 ([#601](https://github.com/MetaMask/snaps-monorepo/pull/601))

## [0.16.0]
### Changed
- No changes this release.

## [0.15.0]
### Fixed
- Fix an issue where comment stripping would break for large files ([#468](https://github.com/MetaMask/snaps-monorepo/pull/468))

## [0.14.0]
### Changed
- **BREAKING:** Increase TypeScript compilation target to ES2020 ([#449](https://github.com/MetaMask/snaps-monorepo/pull/449))
  - This should not be breaking for consumers on any non-deprecated browser or Node.js version.

## [0.13.0]
### Changed
- No changes this release.

## [0.12.0]
### Added
- Initial release ([#410](https://github.com/MetaMask/snaps-monorepo/pull/410), [#421](https://github.com/MetaMask/snaps-monorepo/pull/421))

[Unreleased]: https://github.com/MetaMask/snaps-monorepo/compare/v0.22.4...HEAD
[0.22.4]: https://github.com/MetaMask/snaps-monorepo/compare/v0.22.3...v0.22.4
[0.22.3]: https://github.com/MetaMask/snaps-monorepo/compare/v0.22.2...v0.22.3
[0.22.2]: https://github.com/MetaMask/snaps-monorepo/compare/v0.22.1...v0.22.2
[0.22.1]: https://github.com/MetaMask/snaps-monorepo/compare/v0.22.0...v0.22.1
[0.22.0]: https://github.com/MetaMask/snaps-monorepo/compare/v0.21.0...v0.22.0
[0.21.0]: https://github.com/MetaMask/snaps-monorepo/compare/v0.20.0...v0.21.0
[0.20.0]: https://github.com/MetaMask/snaps-monorepo/compare/v0.19.1...v0.20.0
[0.19.1]: https://github.com/MetaMask/snaps-monorepo/compare/v0.19.0...v0.19.1
[0.19.0]: https://github.com/MetaMask/snaps-monorepo/compare/v0.18.1...v0.19.0
[0.18.1]: https://github.com/MetaMask/snaps-monorepo/compare/v0.18.0...v0.18.1
[0.18.0]: https://github.com/MetaMask/snaps-monorepo/compare/v0.17.0...v0.18.0
[0.17.0]: https://github.com/MetaMask/snaps-monorepo/compare/v0.16.0...v0.17.0
[0.16.0]: https://github.com/MetaMask/snaps-monorepo/compare/v0.15.0...v0.16.0
[0.15.0]: https://github.com/MetaMask/snaps-monorepo/compare/v0.14.0...v0.15.0
[0.14.0]: https://github.com/MetaMask/snaps-monorepo/compare/v0.13.0...v0.14.0
[0.13.0]: https://github.com/MetaMask/snaps-monorepo/compare/v0.12.0...v0.13.0
[0.12.0]: https://github.com/MetaMask/snaps-monorepo/releases/tag/v0.12.0
