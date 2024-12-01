# Changelog

Any notable changes to PyPIz will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- Added a CHANGELOG.md file to monitor the progress of the project.

### Fixed

-  Fix code scanning alert - Starting a process with a partial executable path #23 

## [1.0.1] - 2024-11-28

### Fixed

- Fix code scanning alert - Consider possible security implications associated with subprocess module. #16 
- Fix code scanning alert - subprocess call - check for execution of untrusted input. #14 
- Fix code scanning alert - Using subprocess.run without explicitly set check is not recommended. (subprocess-run-check) #7 
- Fix code scanning alert - Variable name "e" doesn't conform to snake_case naming style #10 
- Fix code scanning alert - Consider explicitly re-raising using the 'from' keyword #13 
- Fix code scanning alert - Too many arguments for logging format string #3 
- Fix code scanning alert - Use lazy % formatting in logging functions (logging-fstring-interpolation) #8 
- Fix code scanning alert - Trailing newlines #11 

[unreleased]: https://github.com/YourLabXYZ/PyPIz/compare/release/v1.0...release/v1.0.2
[1.0.1]: https://github.com/YourLabXYZ/PyPIz/compare/1.0-release...master