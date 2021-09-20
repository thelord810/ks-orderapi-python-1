# Changelog
All notable changes to this project will be documented in this file.

## v1.0.1-BETA (16-Sep-2021)
### Added :
- Support for multiple default hosts. [ Internal ]
- Support to update endpoint's host after generating session according to `redirect` response. [ Internal ]
- Methods to consume Streaming API: `subscribe()` and `unsubscribe()`. For more details, refer [documentation](docs/StreamingApi.md). [ Feature ]
- Method `get_margin()`, For more details, refer [documentation](docs/MarginApi.md#get_margins) [ Feature ]

### Updated:
- In method `session_2fa()`, the `access_code` is now an optional parameter. It is able to generate session token with OTT only. [ Feature ]
- Method `order_report()` now takes an additional boolean parameter `is_fno` whose default value is `False`. [ Feature ]
- The documentation.

### Fixed:

#### Minor:
- `__doc__` strings of few methods.

## v1.0.0-BETA (Unreleased)
### Initial commits.
- For more details, refer [documentation](README.md)