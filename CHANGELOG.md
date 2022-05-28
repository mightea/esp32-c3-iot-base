# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)

<!-- markdownlint-disable no-duplicate-header -->

## [Unreleased]

### Added

- Added changelog
- Adds Pi-filter and resistor to RCWL05-16
- Added new header for externally connecting RCWL-05-16

### Changed

- Moved KiCad project to `pcb` folder
- Reduces board size
- Changed Boot and Reset buttons to Solder Pads to reduce cost

### Removed

- Removed BME280 to reduce cost
- Removed onboard RCWL05-16 due to RF issues

### Fixed

- Connects WS2812 led to 3.3v #3
- Fixes boot issues by updating C5 to 10uf #4

## [0.1] - 2022-05-11

### Added

- Initial fabrication release
