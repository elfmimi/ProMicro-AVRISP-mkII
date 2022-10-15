[![Reseases](https://img.shields.io/github/tag/elfmimi/ProMicro-AVRISP-MKII.svg)](../../releases)
# ProMicro as AVRISP-mkII (fork of [lufa](https://github.com/abcminiuser/lufa))
## Building AVRISP-mkII for ProMicro (ATmega32U4) made easy

This is a fork of lufa to make it easy for anyone to build only one of it's subprojects, namely AVRISP-MKII.

## How to build

`git clone --recursive https://github.com/elfmimi/ProMicro-AVRISP-mkII.git`\
`cd ProMicro-AVRISP-mkII`\
`make`

You'll need avr toolchain.\
In case of Debian/Ubuntu `apt install gcc-avr avr-libc make`

For Windows, download the binary distributed by Microchip.\
https://www.microchip.com/en-us/tools-resources/develop/microchip-studio/gcc-compilers \
You'll also need gnu make command which is found in MSYS2/MinGW or Cygwin.

## License

It is released under modified MIT license as so declared in lufa's README.txt .
