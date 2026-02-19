# Changelog

## [1.1.0] - 2025-02-19

- Added loading animation during time synchronization

## [1.0.9] - 2025-11-09

- Added search functionality to filter accounts by issuer or name
- Search box auto-focuses when popup opens
- Added visual feedback when no accounts match search query

## [1.0.8] - 2025-10-14

- Fixed QR code modal positioning to stay centered when scrolled down in accounts list

## [1.0.7] - 2025-10-13

- Fixed time sync issues
- Prevent backup data from being restored without a password set

## [1.0.6] - 2025-9-07

- Remove time cache; always sync time on popup open and reset TOTP/arc
- Persist `accountsOrder` in both local and sync; read local-first, sync fallback
- Update order in both stores on add/rename/delete/drag to prevent sync order loss

## [1.0.5] - 2025-9-07

- Preserve account order across export/import and UI (uses `accountsOrder`)
- Fix restore race; avoid overwriting order before data is decrypted
- Append new accounts to end of order automatically
- Add time sync: fetch UTC on popup open, cache offset for 5 minutes, use for TOTP and progress arc

## [1.0.4] - 2025-8-17

- Improved drag and drop functionality
- Add sort order persistence to export/import
- Added custom dialog modal (no longer uses system default dialog)
- Added "add account" feature for manual secret entry
- Tested in Chrome Canary as of 8/17/2025

## [1.0.3] - 2025-4-21

- Added drag and drop feature to account list
- Added ability to manually bulk edit accounts

## [1.0.2] - 2025-1-27

- Bug fixes
- Add backup and restore feature

## [1.0.1] - 2025

Initial release
