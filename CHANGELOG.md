# Changelog

All notable changes to gaymersocial.github.io are documented here.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## v1.0.1

### Added
- GitHub Actions CI (`.github/workflows/ci.yml`) checking on every push and pull request against `main` that the key repo files exist, local links resolve, workflow YAML is valid, and `VERSION.md` has a matching `CHANGELOG.md` release heading
- Release workflow (`.github/workflows/release.yml`) that publishes a GitHub Release whenever `commit.sh`'s `vX.Y.Z` tag is pushed, using the matching `CHANGELOG.md` section as the notes

## v1.0.0

### Added
- First version-tracked release of this GitHub Pages redirect repo — `VERSION.md`/`CHANGELOG.md`/`CONTRIBUTING.md`/`commit.sh`+`commit.bat` added, following the standard release-flow convention used across other Stux.Group brand repos

### Fixed
- `README.md`'s header logo pointed at a stale `media.stux.group/global/logo.png` host — corrected to `https://global.media.stux.group/logo.png`
