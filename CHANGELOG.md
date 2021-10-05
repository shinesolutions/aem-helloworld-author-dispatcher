# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

## 0.12.0 - 2021-10-05
### Added
- Add release-major, release-minor, release-patch, and publish Makefile targets and GitHub Actions

### Changed
- Optimise Apache keep alive configurations (KeepAlive On, MaxKeepAliveRequests 0, KeepAliveTimeout 65)

## 0.11.0 - 2020-01-23
### Changed
- Prevents all authenticated pages from being cached

## 0.10.2 - 2019-05-15
### Changed
- Modify build to use aem-platform-buildenv Docker image

## 0.10.1 - 2018-03-26
### Added
- Add https listen port

### Changed
- Parameterise all configuration directories
- Fix secure configuration parameter

## 0.10.0 - 2018-03-20
### Changed
- Update EPP template variables to work with stack provisioner 2.x

## 0.9.0 - 2017-03-02
### Added
- Initial version
