# Open Player

[![GitHub release (latest SemVer)](https://img.shields.io/github/v/release/Sergey842248/Open-Player.svg?logo=github&label=GitHub&cacheSeconds=3600)](https://github.com/Sergey842248/Open-Player/releases/latest)
[![GitHub all releases](https://img.shields.io/github/downloads/Sergey842248/Open-Player/total?logo=github&cacheSeconds=3600)](https://github.com/Sergey842248/open-Player/releases/latest)

Open Player is an Android video player with many features and a clean modern design. It provides a simple and easy-to-use interface for users to play videos on their
Android devices.


**This project is still in development and is expected to have bugs. Please report any bugs you find in
the [Issues](https://github.com/Sergey842248/Open-Player/issues) section.**

[<img src="https://raw.githubusercontent.com/Sergey842248/Open-Player/refs/heads/main/app/src/main/get-it-on-github.png" alt="Get it on GitHub" height="80"/>]([https://play.google.com/store/apps/details?id=dev.anilbeesetti.nextplayer](https://github.com/Sergey842248/Open-Player/releases/latest))

## Screenshots

### Media Picker

<div style="width:100%; display:flex; justify-content:space-between;">

[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/1.png" width=19% alt="Home Light">](fastlane/metadata/android/en-US/images/phoneScreenshots/1.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/2.png" width=19% alt="Home Dark">](fastlane/metadata/android/en-US/images/phoneScreenshots/2.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/3.png" width=19% alt="Sub Folder Light">](fastlane/metadata/android/en-US/images/phoneScreenshots/3.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/4.png" width=19% alt="Sub Folder Dark">](fastlane/metadata/android/en-US/images/phoneScreenshots/4.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/5.png" width=19% alt="Quick Settings">](fastlane/metadata/android/en-US/images/phoneScreenshots/5.png)
</div>

### Player Ui

<div style="width:100%; display:flex; justify-content:space-between;">

[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/6.png" width=49% alt="Player">](fastlane/metadata/android/en-US/images/phoneScreenshots/6.png)
[<img src="fastlane/metadata/android/en-US/images/phoneScreenshots/7.png" width=49% alt="Player">](fastlane/metadata/android/en-US/images/phoneScreenshots/7.png)
</div>

## Supported formats

- **Video**: H.263, H.264 AVC (Baseline Profile; Main Profile on Android 6+), H.265 HEVC, MPEG-4 SP, VP8, VP9, AV1
  - Support depends on Android device
- **Audio**: Vorbis, Opus, FLAC, ALAC, PCM/WAVE (μ-law, A-law), MP1, MP2, MP3, AMR (NB, WB), AAC (LC, ELD, HE; xHE on Android 9+), AC-3, E-AC-3, DTS,
  DTS-HD, TrueHD
  - Support provided by ExoPlayer FFmpeg extension
- **Subtitles**: SRT, SSA, ASS, TTML, VTT, DVB
  - SSA/ASS has limited styling support see [this issue](https://github.com/google/ExoPlayer/issues/8435)

## Features

- Software decoders for h264 and hevc
- Audio/Subtitle track selection
- Vertical swipe to change brightness (left) / volume (right)
- Horizontal swipe to seek through video
- [Material 3 (You)](https://m3.material.io/) support
- Media picker with tree, folder and file view modes
- Play videos from url
- Play videos from storage access framework (Android Document picker)
- Control playback speed
- External Subtitle support
- Zoom gesture
- Picture-in-picture mode

## Improved compared to NextPlayer
### Zoom
#### Max. zoom increased to 2000%
#### Ability to move video while zoomed

### Controls
#### Added option to export current frame


## Contributing

Contributions are welcome!

### Translating

You can help translate Open Player on [Hosted Weblate](https://hosted.weblate.org/engage/next-player/).

[![Translate status](https://hosted.weblate.org/widgets/next-player/-/multi-auto.svg)](https://hosted.weblate.org/engage/next-player/)

## Credits

### Open Source Projects

- [Findroid](https://github.com/jarnedemeulemeester/findroid)
- [Just (Video) Player](https://github.com/moneytoo/Player)
- [LibreTube](https://github.com/libre-tube/LibreTube)
- [ReadYou](https://github.com/Ashinch/ReadYou)
- [Seal](https://github.com/JunkFood02/Seal)
- ...

### Special Thanks

#### Original

![Open Player banner](fastlane/metadata/android/en-US/images/featureGraphic.png)

##### Credits
[<img src="https://hosted.weblate.org/widgets/next-player/-/287x66-white.png"  width="200"/>](https://hosted.weblate.org/engage/next-player/)

Thanks to **Weblate** for providing free hosting for the project.

## License

Open Player is licensed under the GNU General Public License v3.0. See the [LICENSE](LICENSE) file for more information.
