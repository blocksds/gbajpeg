# gbajpeg

## 1. Introduction

This is a library written by Burton Radons designed to decode JPEG files on the
GBA. It's meant to use as few resources as possible, which also makes it very
convenient for other platforms like the NDS.

The library was released under the public domain.

You can see the original website in the Web Archive
[here](https://web.archive.org/web/20230130121359/http://members.iinet.net.au/~freeaxs/gbacomp/#Displaying%20a%20JPEG%20Image%20on%20the%20GBA).

This repository contains the library with a few fixes and a build system so that
the library can be integrated with [BlocksDS](https://github.com/blocksds), a
SDK to develop applications for Nintendo DS.

Note: Progressive and lossless JPEG files aren't supported.

## 2. Install

You can install this library with `wf-pacman` directly:

```bash
wf-pacman -Sy blocksds-gbajpeg
```

If you want to build the library from source, simply run this to build and
install the library in your BlocksDS environment:

```bash
make install
```

## 3. Example

Once you have installed the library, go to the folder of the example and run:

```bash
make
```

This will generate a NDS file that you can test with flashcards or emulators.

## License

This library is released under the public domain.
