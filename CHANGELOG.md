# Changelog

All notable changes by HENSOLDT Cyber GmbH to this 3rd party module included in
the TRENTOS SDK will be documented in this file.

For more details it is recommended to compare the 3rd party module at hand with
the previous versions of the TRENTOS SDK or the baseline version.

## [1.3]

### Changed

- Renamed functions to avoid name clashes or wrong linkage
  (e.g. strlen -> strlen_fv).

### Added

- Added simplified implementations for functions strlen(), memset(), memcmp(),
  strncpy(), memcpy() and strncmp() based on code from musl libc.
