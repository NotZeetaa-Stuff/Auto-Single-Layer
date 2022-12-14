# Auto-Single-Layer
This module switches to Auto Single Layer (Android 13 only)

## What does?
"Android 13 adds a new configuration called AutoSingleLayer for latching unsignaled buffers. This configuration lets SurfaceFlinger latch an unsignaled buffer when only a single layer is updating, and not for the cases that occur across layers, such as geometry changes or sync transactions."

More info: https://source.android.com/docs/core/graphics/unsignaled-buffer-latch
