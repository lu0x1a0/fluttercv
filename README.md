# Flutter CV Project

# Log
## install environment
29-01-2021 - installed android studio. it seems that the android emulator for windows need intel HAXM to run fast. HAXM cant be run along side hyper-v. [SuperUser Stack Exchange Answer](https://superuser.com/questions/1681192/wsl2-android-studio-and-intel-haxm) hyper-v is the basis of wsl2, which I always need. So I will use my phone for all developments. Also the Android Tool Chain is incomplete.

```
> flutter doctor
...
[!] Android toolchain - develop for Android devices (Android SDK version 32.1.0-rc1)
    X cmdline-tools component is missing
      Run `path/to/sdkmanager --install "cmdline-tools;latest"`
      See https://developer.android.com/studio/command-line for more details.
    X Android license status unknown.
      Run `flutter doctor --android-licenses` to accept the SDK licenses.
      See https://flutter.dev/docs/get-started/install/windows#android-setup for more details.
```