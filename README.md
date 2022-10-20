# ReVanced Extended Builder
Credits : [**j-hc/revanced-magisk-module**](https://github.com/j-hc/revanced-magisk-module) and [**inotia00**](https://github.com/inotia00) and [**ReVanced**](https://github.com/revanced)

## Features
 * Can build ReVanced Extended Non-Root APKs
 * Updated daily with the latest versions of apps and patches in accordance with your configuration
 * Cleans APKs from unneeded libs to make them smaller
 * Fully open-source, every binary or APK is compiled without human intervention

## To include/exclude patches or build non-root variant
[**See the list of patches**](https://github.com/inotia00/revanced-patches#-list-of-available-patches)

 * Star the repo :eyes:
 * Use the repo as template or fork it (if you choose the repo to be private, you won't receive updates from Magisk app)
 * Edit the patcher args in [`build.conf`](./build.conf)
 * Run this [workflow](../../actions/workflows/build.yml) 
 * Grab your modules from [releases](../../releases)

**If you include microg patches in [build.conf](./build.conf), you get non-root APKs instead of Magisk modules. Apps except Youtube and Music will always be built as APKs regardless. To be able to use non-root variants of YT and Music you will need to install [Vanced MicroG](https://github.com/TeamVanced/VancedMicroG/releases).**


# Building Locally
Make sure you have JDK 17 installed. Then run:

```console
$ git clone --recurse-submodules https://github.com/j-hc/revanced-magisk-module
$ cd revanced-magisk-module
$ ./build.sh build
```
