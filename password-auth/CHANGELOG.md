# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 0.3.0 (2023-06-24)
### Added
- Derive `Eq`/`PartialEq` on `*Error` ([#433])

### Changed
- Rename `Error` (back) to `VerifyError` ([#432])

[#432]: https://github.com/RustCrypto/password-hashes/pull/432
[#433]: https://github.com/RustCrypto/password-hashes/pull/433

## 0.2.0 (2023-06-24)
### Added
- `is_hash_obsolete` ([#428])

### Changed
- Replace `VerifyError` with `Error` enum ([#429])

[#428]: https://github.com/RustCrypto/password-hashes/pull/428
[#429]: https://github.com/RustCrypto/password-hashes/pull/429

## 0.1.1 (2023-06-01)
### Changed
- Improve documentation ([#419])

[#419]: https://github.com/RustCrypto/password-hashes/pull/419

## 0.1.0 (2023-03-14)
- Initial release
