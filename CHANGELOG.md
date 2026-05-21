# Changelog

All notable changes to the local `hippo/storm` scope will be documented in this file.

## [Unreleased]

### Fixed

- Raise explicit runtime exceptions when GD lacks WebP or AVIF decode support during thumbnail generation instead of triggering undefined-function fatals.
- Catch `Throwable` during attachment thumbnail generation so unsupported image codecs degrade to the broken-image placeholder instead of crashing backend form rendering.
