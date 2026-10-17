# Changelog — `armature-distributed`

All notable changes to this crate will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this crate adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

Earlier changes are recorded in the workspace [`CHANGELOG.md`](../CHANGELOG.md).

## [Unreleased]

## [0.4.0] - 2026-10-17

### Changed

- **Sibling requirements follow the security-hardening release train (breaking).**
  `armature-redis` 0.2 → 0.3. Those releases change public APIs and secure-by-default behaviour
  (see each crate's CHANGELOG); this crate's minor moves with them so a
  downstream build can't mix it with the previous sibling releases. No code
  changes in this crate.

## [0.3.2] - 2026-09-15

### Changed

- Dependencies bumped to their latest releases: `redis` 1.3 → 1.7, `tokio` 1.52 → 1.53, `uuid` 1.23 → 1.26.

