# mbed GCC Makefile

Note: This is old Makefile (few years old). There were plenty of changes in mbed (currently Mbed OS) tree. Therefore this might not build anymore.
Use mbed-cli to build Mbed OS or export (supports exporting to Makefiles for various toolchains). This repo serves as a good example
how to write a simple makefile to build a project with mbed or similar SDK.

### SUPPORTED PLATFORMS GCC_ARM
* KL05Z
* KL25Z
* KL46Z
* LPC1768
* LPC11U24
* LPC11U24_301
* LPC1347
* LPC1114
* LPC11C24
* LPC11U35_401
* STM32F407

If a board is missing, please send a pull request adding it, to keep this up to date. Thanks.

How to use this makefile? I wrote a simple step guide how to create an eclipse project for mbed, used FRDM-KL25Z board: [mbed GCC with eclipse for KL25Z](http://0xc0170.github.io/mbed/2013/08/05/mbed-gcc-with-eclipse-kl25z-part-1/)

If there's an issue, or any improvements can be made, report it in the [issues](https://github.com/0xc0170/mbed_gcc_makefile/issues).

## License
Apache License, Version 2.0

EnjoY!
