# Bitstream Fonts

<img src="./Bitstream_Charter_spec.png" width="300" height="274">

## Introduction

In 1992, Bitstream contributed PostScript versions of the basic Charter BT and Courier 10 Pitch BT families to the X Consortium.
These original files are still available and can be freely downloaded, but they can be hard to find.
So I tracked them down and wrote a script to convert them into a new package of OTFs, TTFs, and webfonts.

## Prerequisites

- [FontForge](https://fontforge.org)

## Build

```bash
$ ./build.sh
$ ls dist/*.zip
dist/CharterBT.zip
dist/Courier10PitchBT.zip
```

## License

See [Copyright](./Copyright).

## Related

- [Utopia](https://github.com/basil/adobe-utopia-type1)
- [Luxi fonts](https://github.com/basil/bh-ttf)
- [IBM Courier](https://github.com/basil/ibm-type1)
- [URW base 35 fonts](https://github.com/basil/urw-base35-fonts)
- [URW free fonts](https://github.com/basil/urw-free-fonts)

## Original

All questions regarding this software should be directed at the
Xorg mailing list:

  https://lists.x.org/mailman/listinfo/xorg

The primary development code repository can be found at:

  https://gitlab.freedesktop.org/xorg/font/bitstream-type1

Please submit bug reports and requests to merge patches there.

For patch submission instructions, see:

  https://www.x.org/wiki/Development/Documentation/SubmittingPatches

