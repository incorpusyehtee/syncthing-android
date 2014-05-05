## syncthing-android

A port of [syncthing](https://github.com/calmh/syncthing) to Android.

## Building

Setup [goandroid](https://github.com/eliasnaur/goandroid).

Then, apply `go_src_pkg_flag.diff` to `src/pkg/flag/flag.go`in your local golang source, and compile and install it.

For syncthing, use [my fork](https://github.com/Nutomic/syncthing/tree/android).

To compile, run `./build.sh` (go cross compile) and `ant -f build.xml clean debug install run` (Android package).
