# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.10.0-rc1] - 2023-01-27

### Added

- N/A

### Changed

- Updating overviews to be in line with current implementations

### Removed

- N/A

## [1.9.0-rc1] - 2022-12-15

### Added

- N/A

### Changed

- N/A

### Removed

- N/A

No Sentinel-1 related modification in this delivery, just a rebuild against the latest version of the services used by the RS add-ons

## [1.8.0-rc1] - 2022-11-23

### Added

- RS-642: Centralized documentation of parameters used within RS add-ons

### Changed

- RS-661: Incorrect routing configuration of Sentinel-1 Level-1 workflow to produce EW_SLC Level-1 outputs

### Removed

- RS-660: S1_L0AIO Remove priority filters

## [1.7.0-rc1] - 2022-10-26

### Added

- RS-508: Process EW L0 only inside AOI given by L0EWSliceMaskCheck (Note that the SLC products are currently not produced due to RS-661)

### Changed

- N/A

### Removed

- N/A

## [1.6.0-rc1] - 2022-09-28

### Added

- N/A

### Changed

- RS-556: rs-addons S1 and S3: wap timeouts are too low

### Removed

- N/A


## [1.5.0-rc1] - 2022-08-31

### Added

- RS-498: Adding a house keep service handling timeout scenarios
- RS-501: Changed location where RS Core Components and images are pushed to

### Changed

- RS-497: Update documentation to be easy to use

### Removed

- N/A

## [1.4.2-rc1] - 2022-17-10

### Added
- N/A

### Changed
- RS-623 / RS-624: [BUG] [OPS] Sentinel-1 AIO preparation job stuck in GENERATING state with mandatory files not found. Backport from 1.5.0.
  WARNING: When using this version ensure that the configuration 'app.preparation-worker.process.hostname' for the RS Add-on is not set to ${HOSTNAME}, but a static unique name.

## [1.4.1-rc1] - 2022-09-22

### Added

- N/A

### Changed

- RS-XX: Merging documentation updates from develop into V1.1

### Removed

- N/A

## [1.4.0-rc1] - 2022-08-03

### Added

- RS-431: Develop S1 L1 processor as a RS-add-on
- RS-432: Develop S1 L2 processor as a RS-add-on
- RS-441: Organize End User documentation for S1

### Changed
- N/A

### Removed
- N/A


## [1.3.0-rc1] - 2022-07-06
### Added
- RS-215: Develop S1 L0ASP processor as a RS-add-on
- RS-216: Develop S1 L0AIO processor as a RS-add-on

### Changed

### Removed
- RS-XX: Removed old V1 style processing chains completely

## [0.3.0-rc1] - 2021-12-18
### Added
- RS-150: S1 L0 AIOP/ASP containers with real IPFs are build

### Changed
- N/A

### Removed
- N/A

## [0.2.0-rc1] - 2021-12-15
### Added
- N/A

### Changed
- N/A

### Removed
- N/A

## [0.1.0-rc1] - 2021-11-17
### Added
- RS-96: A mission identifier is added to traces in order to allow identification of mission

### Changed
- N/A

### Removed
- N/A
