# Changelog

All notable changes to InjectRange are documented here. The format follows Keep
a Changelog, and the project uses semantic versioning.

## [Unreleased]

### Changed

- Probe class wording is under review for the next patch.

## [1.0.4] - 2026-06-30

### Fixed

- The diff command reports guards with equal scores in name order, so two
  runs over the same pair produce the same report.

## [1.0.3] - 2025-10-14

### Added

- JSON output for run and diff.

## [1.0.2] - 2024-09-10

### Fixed

- The corpus verifier folds duplicate probe ids instead of counting them
  twice.

## [1.0.1] - 2023-07-04

### Fixed

- Score ordering is stable for equal breach counts.

## [1.0.0] - 2022-11-22

### Added

- Stable CLI contract for run, corpus, diff, and version, exit codes 0/1/2.
- Tests pin the scoring arithmetic across the bundled guards.

## [0.9.5] - 2021-06-15

### Changed

- Maintenance release: documentation pass and fixture refresh.

## [0.9.0] - 2020-12-01

### Added

- Diff mode comparing two guards against the same corpus.

## [0.8.0] - 2019-08-13

### Added

- Corpus verification: ids unique, classes covered, nothing unreachable.

## [0.7.0] - 2018-10-02

### Added

- Bundled permissive and strict guard profiles.
- README walkthrough captured from a real run.

## [0.6.0] - 2017-04-18

### Added

- Test suite covering classes, harness, and the CLI.
- CLI entry point with subcommands.

## [0.5.0] - 2016-07-26

### Added

- Report renderer with stable per probe lines.
- Harness wiring: one guard evaluated against the whole corpus.

## [0.4.0] - 2015-11-11

