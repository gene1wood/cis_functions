# Changelog

The format is based on [Keep a Changelog](http://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](http://semver.org/spec/v2.0.0.html).

## [Unreleased]

_No changes yet_

## [1.1.1] - 2018-03-07

### Added

#### Full Publisher

- All publishers now require signing.
- All publishers are only authoritative for their namespaces.

#### Blue Green Deploys

- Releases will now be deployed in parallel to allow mozillians and other publishers to simply change the entry point.

### Changed

#### Logging

- Uses CloudWatch Logs for log output.
- Pep8 Functions

### Removed

- Hardcoded URLs have been removed.
- Removed autologin feature for Passwordless logins.

## [1.1] - The past

Major release to switch to full publisher model.