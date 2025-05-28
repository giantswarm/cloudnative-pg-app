# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [0.0.9] - 2025-05-28

### Changed

- Update to cloudnative-pg v1.26.0 (chart v0.24.0).
  - This version allows users to upgrade major versions of postgresql clusters.
  - This version is now using CNPG-I for extensions (like barman for backups).

## [0.0.8] - 2025-05-05

### Changed

- Update to cloudnative-pg v1.25.1 (chart v0.23.2).
- Update <https://github.com/cloudnative-pg/grafana-dashboards> from v0.0.2 to v0.0.4.

## [0.0.7] - 2025-03-20

### Added

- Push to CAPI app collections.

### Changed

- grafana dashboard: load it to `Shared Org` (public) organization

## [0.0.6] - 2024-08-20

### Changed

- Rotate operator-managed certificates 16 days before their expiration, instead of 7 days.
- Update to cloudnative-pg v1.23.2 (chart v0.21.5).

## [0.0.5] - 2024-06-06

### Added

- Package <https://github.com/cloudnative-pg/grafana-dashboards> v0.0.2 with this chart.

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

[Unreleased]: https://github.com/giantswarm/cloudnative-pg-app/compare/v0.0.9...HEAD
[0.0.9]: https://github.com/giantswarm/cloudnative-pg-app/compare/v0.0.8...v0.0.9
[0.0.8]: https://github.com/giantswarm/cloudnative-pg-app/compare/v0.0.7...v0.0.8
[0.0.7]: https://github.com/giantswarm/cloudnative-pg-app/compare/v0.0.7...v0.0.7
[0.0.7]: https://github.com/giantswarm/cloudnative-pg-app/compare/v0.0.6...v0.0.7
[0.0.6]: https://github.com/giantswarm/cloudnative-pg-app/compare/v0.0.5...v0.0.6
[0.0.5]: https://github.com/giantswarm/cloudnative-pg-app/compare/v0.0.4...v0.0.5
[0.0.4]: https://github.com/giantswarm/cloudnative-pg-app/compare/v0.0.3...v0.0.4
[0.0.3]: https://github.com/giantswarm/cloudnative-pg-app/compare/v0.0.2...v0.0.3
[0.0.2]: https://github.com/giantswarm/cloudnative-pg-app/compare/v0.0.1...v0.0.2
[0.0.1]: https://github.com/giantswarm/cloudnative-pg-app/releases/tag/v0.0.1
