---
notification: patch
notification-js: patch
opener: patch
opener-js: patch
---

On Linux and the BSDs, updated `zbus` to version 6, and `notify-rust` to 4.19, its first release on `zbus` 6. The `zvariant`, `zvariant_derive` and `zbus_names` crates, which RustSec flags as unmaintained (RUSTSEC-2026-0370, RUSTSEC-2026-0371 and RUSTSEC-2026-0372), are no longer in the dependency tree of either plugin. The opener's `Error::Zbus` variant now holds a `zbus` 6 error.
