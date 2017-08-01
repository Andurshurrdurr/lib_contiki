# Getting started with contiki
Get the toolchain
## GCC ARM Compiler
https://launchpad.net/gcc-arm-embedded/+milestone/5-2016-q3-update
Download the compiler and add the files in bin to the path. eg add them to ~/bin

## srecord
sudo apt-get install srecord
Stitches together binaries

## How does it work?
The makefile will fetch the toolchain and use it to compile the contiki os with your code

## I had an issue with..
- In the makefile, or when compiled, the board must be specified

