# Release History

## 1.0.0-beta.3 (Unreleased)

### Features Added

### Breaking Changes

### Bugs Fixed

### Other Changes

## 1.0.0-beta.2 (2022-06-30)

### Breaking Changes

- The `Azure::Core::Tracing::OpenTelemetry::OpenTelemetryProvider` type can only be instantiated via a factory method: `OpenTelemetryProvider::Create()`.

### Other Changes

- Removed `_internal` APIs from the public API surface. Also removed most of the `_internal` APIs from the public `opentelemetry.hpp` headers.

## 1.0.0-beta.1 (2022-06-07)

### Features Added

- Initial release
