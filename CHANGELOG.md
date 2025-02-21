# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [1.6.0] - 2022-03-10
### Added
### Changed
### Deprecated
### Removed
### Fixed
- **PODAAC-4307**
  - Added optional dataProcessingType to product. 
### Security

## [1.5.1] - 2020-11-10
### Added
### Changed
### Deprecated
### Removed
### Fixed
- **PODAAC-2733**
  - Updated the CNM schema so product can be used in either the CNM notification or CNM response. 
### Security

## [1.5] - 2020-10-22
### Added
- **PODAAC-2541**
  - a build script under /builder directory, and a jenkins job to build and push release to public github.

### Changed
* Changed 'time' fields to use 'date-time' format
### Deprecated
### Removed
### Fixed
### Security

## [1.4.1] - 2020-08-17
### Added
### changed
* Removed dash from SHA checksumType values to be compatible with Cumulus sync-granule task.
### Deprecated
### Removed
### Fixed
### Security

## [1.4] - 2020-08-12
### Added
### changed
* Removed 'required' fields CHECKSUM and CHECKSUM_TYPE from the file schema
* Added SHA-2 family checksum type to schema
* Added SHA-256, SHA-512 checksum types to schema
### Deprecated
### Removed
### Fixed
### Security


## [1.3] - 2020-04-24
### Added
### changed
* Changed 'ACCESS_ERROR' type to 'TRANSFER_ERROR' type in cnm-response as per CNM ICD.
### Deprecated
### Removed
### Fixed
### Security
