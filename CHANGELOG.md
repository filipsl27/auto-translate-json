# Change Log

## [1.1.3] - 2022-01-31

- Fixed (maybe) pulling proper string out of Azure [topce]

## [1.1.2] - 2022-01-14

- Google changed their authentication so API keys cannot be used anymore. I forced v2 of their library but it's recommended not to use google anymore for this
- Improved detection if extension is triggered directly instead of by right clicking a file.

## [1.1.1] - 2022-01-13

- AWS and Azure, Preprocess text prior to sending as it was for Google (thanks topce)

## [1.1.0] - 2022-01-06

- Added support for AWS and Azure Translation Services (thanks topce)
- Skip tranlation of numbers or booleans (thanks gajo357)
- Added support for deeper folder structures (thanks gajo357)

## [1.0.9] - 2021-03-22

- Added a warning if running this from the command prompt
- upgraded some dependencies

## [1.0.8] - 2020-07-13

- fixed bug on windows by using fsPath instead of path

## [1.0.7] - 2020-07-13

- added more warnings and error reporting

## [1.0.6] - 2020-05-28

- added support for arguments in text strings which won't get translated
- fixed continue after wrong locale file bug
- changed indenting from tabs to double spaces

## [1.0.5] - 2020-05-28

- added support for named arguments
- fixed crash bug related to deeply nested nodes
- added messages for completed locales

## [1.0.4] - 2020-05-27

- restored commented options

## [1.0.3] - 2020-05-27

- added error handling for invalid/unsupported locales

## [1.0.2] - 2020-05-26

- Improved Documentation

## [1.0.1] - 2020-05-26

- fixed bug with mismatched setting names

## [1.0.0] - 2020-05-26

- Initial release of auto-translate-json
