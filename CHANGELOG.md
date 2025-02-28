# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Added
### Changed
### Removed

## [0.14.2] - 2019-10-06
### Added
- JaggedNth supports negative indexing, PR #81 [@pmk21](https://github.com/pmk21!)

## [0.14.1] - 2019-10-04
### Added
- Added version flag to CLI, PR #79. [@maikefischer](github.com/maikefischer)
- Prohibit ncores < 1, PR #76 [@annakau](https://github.com/annakau)

### Changed
- Binned dataframes can now be produced from ND jagged arrays

## [0.14.0] - 2019-10-03
### Added
- Support for ND jagged array in expressions, PR #73
- Automatic conversion of ObjectArrays from uproot to JaggedArrays, PR #73

## [0.13.4] - 2019-09-21
### Changed
- Fixed interpretation of user-defined variables for uproot, issue #67, PR #71 [@benkrikler](https://github.com/benkrikler)

## [0.13.3] - 2019-09-12
### Changed
- Add changes to support uproot 3.9.1 and greater, issue #68 [@benkrikler](https://github.com/benkrikler)

## [0.13.2] - 2019-08-19
### Changed
- Protect against overwriting branches and add tests, pull request #66 [@benkrikler](https://github.com/benkrikler)

## [0.13.1] - 2019-08-05
### Added
- Adds support for masking variables in their definition, issue #59 [@benkrikler](https://github.com/benkrikler)
- Adds several constants for variable expressions, issue #21 [@benkrikler](https://github.com/benkrikler)
- Added this changelog [@benkrikler](https://github.com/benkrikler)

### Changed
- Use `pandas.groupby(..).counts()` to make binned dataframes, issue #51 [@benkrikler](https://github.com/benkrikler)

### Removed

## [0.13.0] - 2019-07-28
### Added
- Add support for multiple output file types for binned dataframes, issue #57 [@asnaylor](https://github.com/asnaylor)

### Changed
- Fix issue with binned dataframe expressions and multiple similar branch names, issue #60 [@benkrikler](https://github.com/benkrikler)
- Enable multiple cut-flow stages and make the input chunk.tree have consistent array and arrays methods, issue #61 [@benkrikler](https://github.com/benkrikler)

### Removed

## [0.12.0] - 2019-05-28
