This is a fork of Brieuc's *dfu commandline* project.

The core of program was changed due wrong dfu generating from gcc hex outputs.
The Program edited in MinGW and Eclipse Mars.1

dfu command line project is intended to be used by stm32 programmers. 

ST released a modified version of DFU called DFUSE, it allows to program the STM32 through it's USB port

dfu_commandline.exe converts a .hex file in a .dfu file following the DFUSE specification

dfucommand.exe then load the code into the target

a tutorial and example is available in the archive
