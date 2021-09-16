# Changelog
All notable changes to this project will be documented in this file.


## v1.0.1-BETA (16-Sep-2021)
### Added :
- Support for multiple default hosts. [ Internal ]
- Support to update endpoint's host after generating session according to `redirect` response. [ Internal ]
- Method to consume Streaming API: `subscribe()` and `unsubscribe()`.

### Updated:
- Method `session_2fa()` to be `access_code` optional parameter, and able to generate session token with OTT only.
- Method `order_report()`, allowing additional boolean value parameter`is_fno`, keeping default value as `False`.
- Related documents.

### Fixed:

#### Minor:
- `__doc__` strings of few methods.

## v1.0.0-BETA (Unreleased)
### Initial commits.
- For more details, refer [documentation](README.md)