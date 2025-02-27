# Amazon ExoPlayer Port

ExoPlayer is an application level open-source media player intended for Android media apps. Amazon has a port of ExoPlayer that is compatible with Fire TV and other Amazon devices.The Amazon port of ExoPlayer provides many fixes, workarounds, and other patches to make ExoPlayer work on Amazon devices.

https://github.com/amzn/exoplayer-amazon-port  
This repository is a port of the ExoPlayer project for Amazon devices.

See https://github.com/google/ExoPlayer for the original project.  
See "README-ORIGINAL.md" for the original ExoPlayer README at [Exoplayer 2.18.7](https://github.com/amzn/exoplayer-amazon-port/blob/amazon/r2.18.7/README-ORIGINAL.md).

 Also see https://developer.amazon.com/docs/fire-tv/media-players.html#exoplayer

## Amazon Port Added Functionality
- Dolby Support on Gen1 FireTV
- Fixes audio latency issues on Gen4 Tablet
- Support for disabling snapping video frame release times to VSYNC added
- Support skipping profile level checks for video added
- Added support for Toshiba Fire TV edition to switch to BT while playing Dolby 
- Framedrops are seen in selected Amazon devices
- Adds a logging mechanism to ease debugging
- Enabled asynchronous buffer queueing mode by default for FTVE devices to reduce frame drops

This functionality was added on top of [Original Exoplayer 2.18.7](https://github.com/google/ExoPlayer/tree/ac9d5337b2b51a855f3c33f3b126d9ef921ebc69)
