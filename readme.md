# Awesome FFmpeg [![Awesome](https://awesome.re/badge.svg)](https://awesome.re) with stars

> [FFmpeg](http://ffmpeg.org) is a cross-platform solution to record, convert and stream audio and video.

<p align="center">
  <img width="400" src="https://cdn.rawgit.com/transitive-bullshit/awesome-ffmpeg/master/ffmpeg-logo.svg">
</p>

## Contents

* [Docs](#docs)
* [JavaScript](#javascript)
* [Native](#native)
* [Mobile](#mobile)
* [Tutorials](#tutorials)
* [Community](#community)

## Docs

FFmpeg's official docs are notoriously difficult for beginners to understand due to the scope and complexity of FFmpeg's capabilities. With that being said, they're still very useful as a reference.

* [FFmpeg.org](http://ffmpeg.org) - Where it all starts.
* [Filters](https://ffmpeg.org/ffmpeg-filters.html) - Docs for FFmpeg's powerful filter chains (scaling, cropping, concatenating, merging, etc.). This is one of my most visited links when working with FFmpeg.
* [Man page](https://man.cx/ffmpeg) - Official FFmpeg man page.
* [Wiki & Bug Tracker](https://trac.ffmpeg.org) - Lots of great info on here.
* [CLI flags](https://github.com/transitive-bullshit/ffmpeg-cli-flags/blob/master/readme.md) ⭐ 50 | 🐛 1 | 📅 2020-07-11 - A comprehensive list of all FFmpeg commandline flags. Really useful for searching random flags that you come across in the wild.

## JavaScript

* [fluent-ffmpeg](https://github.com/fluent-ffmpeg/node-fluent-ffmpeg) ⚠️ Archived - A fluent API to [FFmpeg](http://www.ffmpeg.org). If you only use one tool from this list, it should be this one.
* [editly](https://github.com/mifi/editly) ⭐ 5,153 | 🐛 77 | 🌐 TypeScript | 📅 2025-05-12 - Declarative video editing tool and library with slick animations and transitions.
* [ffmpeg.js](https://github.com/Kagami/ffmpeg.js) ⭐ 3,433 | 🐛 82 | 🌐 JavaScript | 📅 2023-11-04 - Port of FFmpeg to JavaScript via Emscripten. Allows for limited FFmpeg use on the client-side.
* [ffmpeg-static](https://github.com/eugeneware/ffmpeg-static) ⭐ 1,259 | 🐛 27 | 🌐 JavaScript | 📅 2023-12-28 - Provides static FFmpeg binaries for macOS, Linux, and Windows. Very useful for CI testing.
* [ffmpeg-concat](https://github.com/transitive-bullshit/ffmpeg-concat) ⭐ 956 | 🐛 51 | 🌐 JavaScript | 📅 2025-09-24 - Concats a list of videos together using FFmpeg with sexy OpenGL transitions.
* [ffmpeg-generate-video-preview](https://github.com/transitive-bullshit/ffmpeg-generate-video-preview) ⭐ 157 | 🐛 6 | 🌐 JavaScript | 📅 2018-08-09 - Generates an attractive image strip or GIF preview from a video.
* [ffmpeg-extract-frames](https://github.com/transitive-bullshit/ffmpeg-extract-frames) ⭐ 64 | 🐛 8 | 🌐 JavaScript | 📅 2020-12-11 - Extracts screenshots from a video using FFmpeg.
* [gif-extract-frames](https://github.com/transitive-bullshit/gif-extract-frames) ⭐ 32 | 🐛 1 | 🌐 JavaScript | 📅 2020-07-11 - Extracts frames from GIFs including inter-frame coalescing.
* [ffmpeg-extract-audio](https://github.com/transitive-bullshit/ffmpeg-extract-audio) ⭐ 18 | 🐛 2 | 🌐 JavaScript | 📅 2020-07-11 - Extracts an audio stream from a media file.
* [ffmpeg-extract-frame](https://github.com/transitive-bullshit/ffmpeg-extract-frame) ⭐ 16 | 🐛 15 | 🌐 JavaScript | 📅 2022-12-07 - Extracts a single frame from a video.
* [ffmpeg-probe](https://github.com/transitive-bullshit/ffmpeg-probe) ⭐ 15 | 🐛 12 | 🌐 JavaScript | 📅 2023-01-25 - Wrapper around ffprobe for getting info about media files.
* [ffmpeg-on-progress](https://github.com/transitive-bullshit/ffmpeg-on-progress) ⭐ 14 | 🐛 1 | 🌐 JavaScript | 📅 2020-07-11 - Utility for robustly reporting progress with fluent-ffmpeg.
* [ffparser](https://github.com/NiKlimenko/FFParser) ⭐ 7 | 🐛 0 | 🌐 TypeScript | 📅 2019-05-26 - Parse input stream by frames directly into your code as a buffer.
* [tangerine](https://github.com/niftylettuce/tangerine) - Webcam streaming service using Node.js, FFmpeg, WebSockets, and Lad.

## Native

* [ffmpeg-gl-transition](https://github.com/transitive-bullshit/ffmpeg-gl-transition) ⭐ 701 | 🐛 36 | 🌐 C | 📅 2024-07-23 - FFmpeg filter for applying GLSL transitions between video streams ([gl-transitions](https://gl-transitions.com/)).

## Mobile

* [ijkplayer](https://github.com/Bilibili/ijkplayer) ⭐ 33,005 | 🐛 2,891 | 🌐 C | 📅 2024-08-13 - Android / iOS video player based on FFmpeg.
* [simplest ffmpeg mobile](https://github.com/leixiaohua1020/simplest_ffmpeg_mobile) ⭐ 1,940 | 🐛 64 | 🌐 C | 📅 2016-04-19 - FFmpeg examples for Android and iOS.

## Tutorials

* [Learn FFmpeg libav the Hard Way](https://github.com/leandromoreira/ffmpeg-libav-tutorial) ⭐ 10,623 | 🐛 42 | 🌐 C | 📅 2025-02-01
* [FFmpeg Cheatsheet for Video Automation](https://github.com/rendi-api/ffmpeg-cheatsheet) ⭐ 473 | 🐛 2 | 📅 2025-09-18
* [A Beginner's FFmpeg Cookbook](https://github.com/talwrii/ffmpeg-cookbook) ⭐ 79 | 🐛 1 | 📅 2025-07-15
* [How to Write a Video Player in Less Than 1k Lines](http://dranger.com/ffmpeg)
* [Applying OpenGL Shaders with FFmpeg](https://nervous.io/ffmpeg/opengl/2017/01/31/ffmpeg-opengl) - And [follow-up](https://nervous.io/ffmpeg/opengl/2017/05/15/ffmpeg-pbo-yuv).

## Community

* [Stack Overflow](https://superuser.com/questions/tagged/ffmpeg)
* [Mailing Lists](https://www.ffmpeg.org/contact.html#MailingLists)
* [IRC](https://www.ffmpeg.org/contact.html#IRCChannels)

## Contribute

Contributions welcome! Please read the [contributing guideline](origin/contributing.md) first.

## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, [Travis Fischer](https://github.com/transitive-bullshit) has waived all copyright and related or neighboring rights to this work.

Support my OSS work by <a href="https://twitter.com/transitive_bs">following me on twitter <img src="https://storage.googleapis.com/saasify-assets/twitter-logo.svg" alt="twitter" height="24px" align="center"></a>
