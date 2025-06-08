# record_linux

Linux specific implementation for record package called by record_platform_interface.

## Build information
- Base audio system is PulseAudio. It will assume basic PulseAudio libraries are available in the system (typically the case for most distributions).
- Makes use of `parecord` and `ffmpeg` for the purpose of recording and encoding.
- Requires `libgstreamer1.0-dev` and `libgstreamer-plugins-base1.0-dev` in the build environment
