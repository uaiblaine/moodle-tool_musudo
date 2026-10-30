# Change log

Plugin versioning is derived from Moodle releases, it does not comply with the semantic versioning standard.

The format of this change log follows the advice given at [Keep a CHANGELOG](https://keepachangelog.com).

## [Unreleased]

### Changed

- migration to new forms library
- privilege contexts are selected by level (system, tenant, category, course) with searchable pickers
  instead of typing numeric context ids, context ids can still be entered for other contexts

### Fixed

- the MFA factor description on the privileged session page showed its HTML tags as text
  (the e-mail factor's `<strong>` around the obfuscated address)
