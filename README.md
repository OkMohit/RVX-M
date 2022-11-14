# ReVanced Extended Builder 
[![Build Modules](https://github.com/j-hc/revanced-magisk-module/actions/workflows/build.yml/badge.svg)](https://github.com/OkMohit/RVX-M/blob/main/.github/workflows/build.yml)

## Features
 * Can build 2 Non-root RVX apk's at single Workflow (currently set to Amoled + Monet)
 * Removed all unneeded libs to make them smaller (by default armv8)
 * Fully open-source, every binary or APK is compiled without human intervention

## To include/exclude patches
[**List of Patches Available**](https://github.com/inotia00/revanced-patches#-list-of-available-patches)

 * Use the repo as template or fork it.
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

