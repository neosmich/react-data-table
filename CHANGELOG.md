# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [3.6.0] - 2023-10-26

### Changed

- Updated react-pattern-ui from 2.4.0 to 2.9.0

## [3.5.0] - 2023-10-05

### Added

- Added function `getFilterState` to get current status of filters
- Added function `updateFilters` to update filters and refresh dataTable

## [3.4.0] - 2023-10-03

### Added

- Added nullable `disabled` prop to `EnumValue` type

## [3.3.0] - 2023-08-07

### Changed

- Updated react-pattern-ui to 2.4.0

## [3.2.0] - 2023-08-04

### Added

- Added support to "react" version "^18.0.0" in peerDependencies
- Added support to "react-dom" version "^18.0.0" in peerDependencies
- Added support to "reactstrap" version "^9.0.0" in peerDependencies
- Added support to "@fortawesome/react-fontawesome" version "^0.2.0" in peerDependencies

### Fixed

- Fixed export for CommonJS

## [3.1.0] - 2023-08-03

### Changed

- Updated react-pattern-ui to 2.3.0

## [3.0.0] - 2023-07-26

# Changed

- :boom: `view` default Action does not nest an `<a>` tag anymore.

## [2.7.3] - 2023-06-29

### Changed

- `orderBy` property of `QueryFunction` type can be string or undefined.

## [2.7.2] - 2023-06-29

### Fixed

- Excluded test code from the package and made sure the paths are pointing to the correct `.d.ts` files

## [2.7.1] - 2023-06-16

### Fixed

- update types file location in package.json

## [2.7.0] - 2023-06-16

### Fixed

- update `@neolution-ch/react-pattern-ui` to the latest version (2.2.1)

## [2.6.1] - 2023-06-13

### Fixed

- Moved `@neolution-ch/react-pattern-ui` to the dependencies, so it gets correctly detected by rollup as an external dependency

## [2.6.0] - 2023-06-12

### Changed

- Changed from `microbundle` to `rollup` for building the package
- Updated all the dependencies to the latest possible version

### Fixed

- Display predefined filter in filter row

## [2.5.0] - 2023-05-25

### dependabot: \#33 Bump loader-utils from 1.4.0 to 1.4.2

## [2.4.1] - 2023-05-25

### Added

- the prop `enablePredefinedSort` to all tables. Set boolean condition for which the orderBy option should be ignored. Set as `false` by default if not specified.

## [2.4.0] - 2023-05-17

### Added

- the prop `rowHighlight` to all tables. Check `RowHighlightInterface` for prop definition. Set condition for which a row should be highlighted. Possibility to set custom style for highlights

## [2.3.2] - 2023-03-08

### Added

- the style 'white-space:no-wrap' to default 'ActionCell' to have icons on the same line

## [2.3.1] - 2023-03-07

### Changed:

- depandabot: Bump ejs from 3.1.6 to 3.1.8

## [2.3.0] - 2023-03-06

### Added

- the prop `icon` to the `DataTablePredefinedActionLink` interface to specify the view action column icon. Possible values are all `IconProp`. The default value is the eye icon `faEye`

## [2.2.0] - 2023-02-22

### Added

- the prop `actionsPosition` to the `DataTable` component to specify the position of the actions column. Possible values are `left` and `right`. The default value is `left`.

## [2.1.2] - 2022-06-20

### Added

- Added asc prop to specify the arrow icon sorting direction
- Added orderBy prop to specify the sorting key value

## [2.1.1] - 2022-05-04

### Changed

- Moved storybook to github pages

## [2.1.0] - 2022-05-02

### Added

- Dynamic table handler to reload the data from an external source.
- Added new story to reload data with sample code.
- Implemented className and style properties to the table and the actions.
- Added reload tests.

### Changed

- Changed max-lines allowed in DataTableInterfaces.ts.
- Changed max-lines allowed in DataTableRouted.tsx.

## [2.0.3] - 2022-04-19

### Added

- Story book

## [2.0.2] - 2022-04-14

### Changed

- Upgraded @neolution-ch/react-pattern-ui dependency to 2.0.2

## [2.0.1] - 2022-04-14

### Fixed

- Fix added for missing react import aftger microbundling

## [2.0.0] - 2022-04-12

### Added

- created package :tada:

[unreleased]: https://github.com/neolution-ch/react-data-table/compare/3.6.0...HEAD
[3.6.0]: https://github.com/neolution-ch/react-data-table/compare/3.5.0...3.6.0
[3.5.0]: https://github.com/neolution-ch/react-data-table/compare/3.4.0...3.5.0
[3.4.0]: https://github.com/neolution-ch/react-data-table/compare/3.3.0...3.4.0
[3.3.0]: https://github.com/neolution-ch/react-data-table/compare/3.2.0...3.3.0
[3.2.0]: https://github.com/neolution-ch/react-data-table/compare/3.1.0...3.2.0
[3.1.0]: https://github.com/neolution-ch/react-data-table/compare/3.0.0...3.1.0
[3.0.0]: https://github.com/neolution-ch/react-data-table/compare/2.7.3...3.0.0
[2.7.3]: https://github.com/neolution-ch/react-data-table/compare/2.7.2...2.7.3
[2.7.2]: https://github.com/neolution-ch/react-data-table/compare/2.7.1...2.7.2
[2.7.1]: https://github.com/neolution-ch/react-data-table/compare/2.7.0...2.7.1
[2.7.0]: https://github.com/neolution-ch/react-data-table/compare/2.6.1...2.7.0
[2.6.1]: https://github.com/neolution-ch/react-data-table/compare/2.6.0...2.6.1
[2.6.0]: https://github.com/neolution-ch/react-data-table/compare/2.5.0...2.6.0
[2.5.0]: https://github.com/neolution-ch/react-data-table/compare/2.4.0...2.5.0
[2.4.0]: https://github.com/neolution-ch/react-data-table/compare/2.3.2...2.4.0
[2.3.2]: https://github.com/neolution-ch/react-data-table/compare/2.3.1...2.3.2
[2.3.1]: https://github.com/neolution-ch/react-data-table/compare/2.3.0...2.3.1
[2.3.0]: https://github.com/neolution-ch/react-data-table/compare/2.2.0...2.3.0
[2.2.0]: https://github.com/neolution-ch/react-data-table/compare/2.1.2...2.2.0
[2.1.2]: https://github.com/neolution-ch/react-data-table/compare/2.1.1...2.1.2
[2.1.1]: https://github.com/neolution-ch/react-data-table/compare/2.1.0...2.1.1
[2.1.0]: https://github.com/neolution-ch/react-data-table/compare/2.0.3...2.1.0
[2.0.3]: https://github.com/neolution-ch/react-data-table/compare/2.0.2...2.0.3
[2.0.2]: https://github.com/neolution-ch/react-data-table/compare/2.0.1...2.0.2
[2.0.1]: https://github.com/neolution-ch/react-data-table/compare/2.0.0...2.0.1
[2.0.0]: https://github.com/neolution-ch/react-data-table/compare/429b3a1c042143eeb0d4e3ec1a50e81faf33e384...2.0.0
