# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.0.1]
### Changed
- Relax dependency on `@metamask/base-controller` and `@metamask/permission-controller` (use `^` instead of `~`) ([#998](https://github.com/MetaMask/core/pull/998))

## [1.0.0]
### Added
- Initial release
  - As a result of converting our shared controllers repo into a monorepo ([#831](https://github.com/MetaMask/core/pull/831)), we've created this package from select parts of [`@metamask/controllers` v33.0.0](https://github.com/MetaMask/core/tree/v33.0.0), namely:
    - Everything in `src/subject-metadata`

    All changes listed after this point were applied to this package following the monorepo conversion.
- Add method to get subject metadata by origin ([#950](https://github.com/MetaMask/core/pull/950))

[Unreleased]: https://github.com/MetaMask/core/compare/@metamask/subject-metadata-controller@1.0.1...HEAD
[1.0.1]: https://github.com/MetaMask/core/compare/@metamask/subject-metadata-controller@1.0.0...@metamask/subject-metadata-controller@1.0.1
[1.0.0]: https://github.com/MetaMask/core/releases/tag/@metamask/subject-metadata-controller@1.0.0
