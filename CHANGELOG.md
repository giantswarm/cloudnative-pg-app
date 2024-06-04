# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.0.4] - 2024-06-04

### Added

- Push to AWS app collection.

### Changed

- Extend CiliumNetworkPolicy to cover CNPG join and init operations.

## [0.0.3] - 2024-05-17

### Added

- Add CiliumNetworkPolicy.
- Enable PodMonitor for operator metrics.
- Enable Grafana dashboard.
- Enable ClusterImageCatalog for Giant Swarm retagged images.

## [0.0.2] - 2024-04-30

### Changed

- Change app catalog from `giantswarm` to `operations`.
- Update to cloudnative-pg v1.23.1 (chart v0.21.2).
- Increase default CPU requests to 250Mi.

## [0.0.1] - 2024-04-17

- Initial release containing cloudnative-pg v1.22.2 (chart v0.20.2).

[Unreleased]: https://github.com/giantswarm/cloudnative-pg-app/compare/v0.0.4...HEAD
[0.0.4]: https://github.com/giantswarm/cloudnative-pg-app/compare/v0.0.3...v0.0.4
[0.0.3]: https://github.com/giantswarm/cloudnative-pg-app/compare/v0.0.2...v0.0.3
[0.0.2]: https://github.com/giantswarm/cloudnative-pg-app/compare/v0.0.1...v0.0.2
[0.0.1]: https://github.com/giantswarm/cloudnative-pg-app/releases/tag/v0.0.1
