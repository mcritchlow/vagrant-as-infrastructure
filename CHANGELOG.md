# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

## [1.1.0] - 2018-10-18
### Added
- `file`, `shell`, and `ansible` provisioners in Vagrantfile/GUESTS.rb

### Changed
- Default box is `ubuntu/bionic64`
- Installs python/python-apt on boxes with `debian` or `ubuntu` in their name
- Only running boxes have their ssh configurations queried

## [1.0.1] - 2018-10-17
### Added
- `copyright` and `license` targets

## [1.0.0] - 2018-10-16
### Added
- First Public Release
