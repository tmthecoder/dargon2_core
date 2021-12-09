## 2.0.0
- BREAKING: All `sync` ending methods have been removed. Please use the asynchronous methods
- Web support comes with dargon2_core, which was the reason for removing the sync methods as maintaining the same interface requires async-only due to web

## 1.0.0

- Initial version.
- Moved all bindings (function mappings from C to Dart) here instead of dargon2
- dargon2 and dargon2_flutter both share inheritance off this plugin and handle library loading in their respective plugins
