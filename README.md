Abrowser for Android
=====================

Android version of Abrowser - GNU Trisquel's version of Firefox [https://trisquel.info/en/wiki/abrowser-help](https://trisquel.info/en/wiki/abrowser-help).

You can download prebuilt APK's from [Release](https://github.com/proninyaroslav/abrowser-android/releases) section or from [mirror](https://proninyaroslav.ru/ftp/abrowser_android/).

## Building

At the moment build script only works on Linux (maybe BSD or Mac), many necessary dependencies are installed automatically or they need to be installed manually (the build system will inform you about it).

For more information about building, you can read the [official documentation](https://developer.mozilla.org/en-US/docs/Mozilla/Developer_guide/Build_Instructions/Simple_Firefox_for_Android_build).

### Build steps

1. Run `build_apk` script, source tarball is downloaded and unpacked automatically. You can edit it for your needs.
2. Follow the steps of the build system; choose `3. Firefox for Android Artifact Mode` when prompted.
3. Generated APK will be located in `BUILD_DIR/obj-droid/dist`.
