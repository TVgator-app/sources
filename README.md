# TVgator — corresponding source code

This repository provides the complete corresponding source code of the open-source libraries that are
shipped in the TVgator app, as their licenses require (GNU LGPL 2.1 or later, GNU LGPL 3.0 or later, and
others). The app itself is not open source.

Each release holds one source package. Its tag is the name under which the license screen of the app
refers to it; a published package is never replaced — a new build gets a new tag.

- `libvlc-source-…` — libVLC (from VLC 3.0.25) with libvlcjni, as built for Android: the source tree in
  the state that was compiled, the dated modifications, the original source archives of all libraries
  linked into libvlc.so, and the build instructions.
- `ffmpeg-source-…` — FFmpeg (branch release/6.0) and the Media3 FFmpeg extension, as built for Android,
  with the build scripts.

Each archive contains a README.txt describing its contents and how to rebuild.
