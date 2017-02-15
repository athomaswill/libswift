# libswift

## Adding versions

Run `make copy [SWIFT=<version>] [XCODE=</path/to/Xcode.app>]`

## Building

    make [V=<version>]

If you don't set V, the latest major version will be used (eg. 3).

## Installing

    make install [THEOS_]DEVICE_IP=<ip> [[THEOS_]DEVICE_PORT=<port>]

If neither `DEVICE_PORT` nor `THEOS_DEVICE_PORT` is set, port 22 will be used.
