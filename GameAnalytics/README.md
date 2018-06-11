# GameAnalytics

Modified CPP SDK: https://github.com/leyyin/GA-SDK-CPP

Modified UNREAL SDK: https://github.com/leyyin/GA-SDK-UNREAL


Version `2.6.15`

Copied manually from https://github.com/GameAnalytics/GA-SDK-UNREAL
because it is the latest version and also on linux we do not have a marketplace.

## Documentation
1. https://gameanalytics.com/docs/unreal4-sdk
2. https://gameanalytics.com/docs/


## Build

NOTE: use the modified CPP SDK, otherwise the build/link will fail.

Windows:
```sh
./build.sh -n -t win64-vc140-static
./build.sh -n -t win32-vc140-static
```

Linux:
```
./build.sh -n linux-x64-static
```
