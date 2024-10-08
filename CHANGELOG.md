# Changelog

Observes [Semantic Versioning](https://semver.org/spec/v2.0.0.html) standard and
[Keep a Changelog](https://keepachangelog.com/en/1.0.0/) convention.

## [0.5.0] - 2023-01-09

+ Remove - `recursive_search` function
+ Add - pre-commit checks to the repo to observe flake8, black, isort
+ Add - `value_to_bool` and `QuietStdOut` utilities

## [0.4.2] - 2022-12-16

+ Update - PrairieView loader checks for multi-plane vs single-plane scans.

## [0.4.1] - 2022-12-15

+ Update - PrairieView loader now reads recording start time from metadata file

## [0.4.0] - 2022-12-14

+ Add - mkdocs documentation
+ Add - improved docstrings for mkdocs
+ Add - EXTRACT trigger and loader tools

## [0.3.0] - 2022-10-7

+ Add - Function `prairieviewreader` to parse metadata from Bruker PrarieView acquisition
    system
+ Update - Changelog with tag links

## [0.2.1] - 2022-07-13

+ Add - Adopt `black` formatting
+ Add - Code of Conduct

## [0.2.0] - 2022-07-06

+ First release of `element-interface`.
+ Bugfix - Fix for `tifffile` import.
+ Add - Function `run_caiman` to trigger CNMF algorithm.
+ Add - Function `ingest_csv_to_table` to insert data from CSV files into tables.
+ Add - Function `recursive_search` to search through nested dictionary for a key.
+ Add - Function `upload_to_dandi` to upload Neurodata Without Borders file to the DANDI
    platform.
+ Update - Remove `extras_require` feature to allow this package to be published to PyPI.

## [0.1.0a1] - 2022-01-12

+ Change - Rename the package `element-data-loader` to `element-interface`.

## [0.1.0a0] - 2021-06-21

+ Add - Readers for: `ScanImage`, `Suite2p`, `CaImAn`.

[0.5.0]: https://github.com/datajoint/element-interface/releases/tag/0.5.0
[0.4.2]: https://github.com/datajoint/element-interface/releases/tag/0.4.2
[0.4.1]: https://github.com/datajoint/element-interface/releases/tag/0.4.1
[0.4.0]: https://github.com/datajoint/element-interface/releases/tag/0.4.0
[0.3.0]: https://github.com/datajoint/element-interface/releases/tag/0.3.0
[0.2.1]: https://github.com/datajoint/element-interface/releases/tag/0.2.1
[0.2.0]: https://github.com/datajoint/element-interface/releases/tag/0.2.0
[0.1.0a1]: https://github.com/datajoint/element-interface/releases/tag/0.1.0a1
[0.1.0a0]: https://github.com/datajoint/element-interface/releases/tag/0.1.0a0
