# Build [FFmpeg](https://ffmpeg.org) with brew on macOS [![](https://travis-ci.org/cntrump/brew-build-ffmpeg.svg?branch=master)](https://travis-ci.org/cntrump/brew-build-ffmpeg)

- Base on static library recommended by ffmpeg.org: [Static builds for macOS 64-bit](https://evermeet.cx/ffmpeg/)
- Add AAC support
- Add SSL support (with [OpenSSL](https://www.openssl.org))
- Requirement minimum macOS version: 10.9

## How to use

### Install [Homebrew](https://brew.sh)

```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install.sh)"
```

### Build FFmpeg

Run `build.sh`

```shell
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/cntrump/brew-build-ffmpeg/master/build.sh)"
```

### Finished

ffmpeg installed to

- `/usr/local/bin/ffmpeg`
- `/usr/local/bin/ffprobe`

### Pre-Built Binaries

[Here](https://github.com/cntrump/brew-build-ffmpeg/releases)

## Linux users

[ubuntu-build-ffmpeg](https://github.com/cntrump/ubuntu-build-ffmpeg)
