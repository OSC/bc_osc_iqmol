# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]
## [0.3.0] - 2020-01-19
### Added
- [4](https://github.com/OSC/bc_osc_iqmol/pull/4)
  - removed owens-slurm and torque related items
  - account is now a select widget with only valid groups as options

## [0.2.0] - 2020-11-18
### Added
- Added owens-slurm cluster to begin migrating Owens to Slurm in
  [3](https://github.com/OSC/bc_osc_iqmol/pull/3)

### Fixed
- Fixed num_cores to be better labeled and a number_field also in
  [3](https://github.com/OSC/bc_osc_iqmol/pull/3)

## [0.1.2] - 2020-09-10
### Fixed
- This broke XFCE Panels, removing them. So we just dropped using them altogether.

### Added
- Added the option to specify how many hours users can schedule the job for.

## [0.1.1] - 2020-09-03
### Fixed
- BINDPATH did not include $OSC_QCHEM_DIR so it could not launch qchem

## 0.1.0 - 2020-09-03
- Initial release!

[Unreleased]: https://github.com/OSC/bc_osc_iqmol/compare/v0.3.0...HEAD
[0.3.0]: https://github.com/OSC/bc_osc_iqmol/compare/v0.2.0...v0.3.0
[0.2.0]: https://github.com/OSC/bc_osc_iqmol/compare/v0.1.2...v0.2.0
[0.1.2]: https://github.com/OSC/bc_osc_iqmol/compare/v0.1.1...v0.1.2
[0.1.1]: https://github.com/OSC/bc_osc_iqmol/compare/v0.1.0...v0.1.1
