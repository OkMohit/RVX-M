# ReVanced Magisk Module
[![Build Modules](https://github.com/j-hc/revanced-magisk-module/actions/workflows/build.yml/badge.svg)](https://github.com/OkMohit/RVX-M/blob/main/.github/workflows/build.yml)

## Features
 * Can build Non-root APK
 * Updated daily with the latest versions of apps and patches in accordance with your configuration
 * Cleans APKs from unneeded libs to make them smaller (by default armv8)
 * Fully open-source, every binary or APK is compiled without human intervention

## To include/exclude patches
[**See the list of patches**](https://github.com/revanced/revanced-patches#-list-of-available-patches)

 * Star the repo :eyes:
 * Use the repo as template or fork it (if you choose the repo to be private, you won't receive updates from Magisk app)
 * Edit the patcher args in [`build.conf`](./build.conf)
 * Run the [workflow](../../actions/workflows/build.yml)
 * Grab your apk from [releases](../../releases)

To be able to use non-root variants of YT and Music you will need to install [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases).**

# Building Locally
Make sure you have JDK 17 installed. Then run:

```console
$ git clone --recurse-submodules https://github.com/j-hc/revanced-magisk-module
$ cd revanced-magisk-module
$ ./build.sh build
```

