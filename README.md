# Awesome-Embedded
A curated list of awesome embedded resource.

Table of content

* [Interview](#interview)
* [Embedded Software Skill](#embedded-software-skill)
* [Common](#common)
* [Microcontroller](#mcu-programming)
    * [TM4C123](#tm4c123)
    * [STM32](#stm32)
    * [MSP430](#msp430)
    * [MSP432](#msp432)
    * [STM8](#stm8)
* [Raspberry](#raspberry)
* [Bealgebone](#beaglebone)
* [Assembly](#assembly)
* [Linux Programming](#linux-programming)
* [RTOS](#rtos)
* [AUTOSAR](#autosar)
* [OS](#os)
* [Compiler](#compiler)
* [Bootloader](#bootloader)
* [Others](#ohers)
* [Tips & tricks](#tips-&-tricks)
* [FAQ - Embedded](#faq_embedded)

## Interview

* [Questions which are frequently asked in an interview.](https://github.com/Embedded-Systems-Guide/interview-questions)
> On the way to be a full-stack embedded software engineer.

## Embedded Software Skill

* [Skills/Knowledge required to become a champion Embedded Software Developer.](https://github.com/Embedded-Systems-Guide/embedded-software-skills)
* [How to be low-level programmer](https://github.com/gurugio/lowlevelprogramming-university)
* [Programmer Competency Matrix](http://sijinjoseph.com/programmer-competency-matrix/)

## Common

* [Integer size in C on 32-bit and 64-bit system](https://usrmisc.wordpress.com/2012/12/27/integer-sizes-in-c-on-32-bit-and-64-bit-linux/)
* [TeraTerm - TTL command reference](http://ttssh2.osdn.jp/manual/en/macro/command/index.html)
* [TeraTerm Scripts](http://processors.wiki.ti.com/index.php/Teraterm_Scripts)
* [Linker Command File Primer](http://processors.wiki.ti.com/index.php/Linker_Command_File_Primer)
* [The C build process](https://blog.feabhas.com/2012/06/the-c-build-process/)
* [Building Bare-Metal ARM Systems with GNU](https://www.embedded.com/design/mcus-processors-and-socs/4026111/Building-Bare-Metal-ARM-Systems-with-GNU-Part-9)
* [ELF – Executable and Linkable Format](https://2wisebit.wordpress.com/2018/06/08/elf-executable-and-linkable-format/)
* [Toolchains](https://web.eecs.umich.edu/~prabal/teaching/resources/eecs373/toolchain-notes.pdf)
* [What is an application binary interface (ABI)?](https://stackoverflow.com/questions/2171177/what-is-an-application-binary-interface-abi)
* [ ARM Cortex M4 Blink Example (Linker Script)](http://robotics.mcmanis.com/src/arm-blink/linker-script.html)
* [A Sample Linker Script](http://hertaville.com/a-sample-linker-script.html)
* [Linking and Loading](http://www.iecc.com/linker/linker01.html)
* [Embedded Software _ Getting started](http://www2.thu.edu.tw/~emtools/DOE_project/NCCU/embedded%20system/ESD_06_GettingStarted.pdf)
* [How to convert from an armlink scatter file to a GNU ld linker script](https://www.mayrhofer.eu.org/node/24)
* [Using the GNU Linker](https://www.math.utah.edu/docs/info/ld_3.html)

## MCU programming

### Bare-metal programming (Don't need MCU)

* [Simplest bare metal program for ARM](https://balau82.wordpress.com/2010/02/14/simplest-bare-metal-program-for-arm/) ([table of content](https://balau82.wordpress.com/arm-emulation/))

### MSP430
* [MSP430-GCC](http://www.simplyembedded.org/tutorials/setting-up-a-virtual-machine/)

### TM4C123
* [Analog to Digital Conversion, Data Acquisition and Control](http://users.ece.utexas.edu/~valvano/Volume1/E-Book/C14_ADCdataAcquisition.htm)
* [Embedded Systems - Shape The World](http://users.ece.utexas.edu/~valvano/Volume1/E-Book/)
* [HowTo: Develop on the TI Tiva LaunchPad using Linux](http://chrisrm.com/howto-develop-on-the-ti-tiva-launchpad-using-linux/)
* [Linux command line build system to generate binaries for TM4C123 (ARM Cortex M4) ](https://github.com/pitankar/TM4C)
* [The complete tutorial for Stellaris LaunchPad development with GNU/Linux (I) ](http://kernelhacks.blogspot.com/2012/11/the-complete-tutorial-for-stellaris.html)
* [Getting Started with the TI Stellaris LaunchPad on Linux](https://www.jann.cc/2012/12/11/getting_started_with_the_ti_stellaris_launchpad_on_linux.html)
* [Embedded Systems with TM4C123 @Valvano](http://users.ece.utexas.edu/~valvano/arm/)

### MSP432

### STM32
* [STM32 bootloader](http://ciesie.com/ks_stm32_bootloader.html)
* [Tests to program STM32 Nucleo in C with GCC ARM embedded toolchain and libopencm3](https://github.com/balau/nucleo_tests)
* [A demo project of FreeRTOS running on a STM32F4 Discovery board. ](https://github.com/wangyeee/STM32F4-FreeRTOS)
* [DFU Bootloader for STM32 chips](https://github.com/devanlai/dapboot)

### STM8


## Raspberry

* [ChibiOS/RT on the Raspberry Pi](https://www.stevebate.net/chibios-rpi/GettingStarted.html)
* [Raspberry Pi ARM based bare metal examples ](https://github.com/dwelch67/raspberrypi)
* [Bare metal Raspberry Pi 3 tutorials ](https://github.com/bztsrc/raspi3-tutorial)
* [Open Projects: Raspberry, Beaglebone BSP](https://devel.rtems.org/wiki/Developer/OpenProjects)
* [A Real-Time Operating System on the Raspberry Pi](http://www.pebblebay.com/raspberry-pi-embedded/)
* [A port of FreeRTOS to the raspberry pi](https://github.com/jameswalmsley/RaspberryPi-FreeRTOS)
* [FreeRTOS Sucessfully Ported](https://www.raspberrypi.org/forums/viewtopic.php?f=72&t=22423)
* [Exploring AArch64 assembler - Raspberry](https://thinkingeek.com/2016/10/08/exploring-aarch64-assembler-chapter1/)
* [A bootloader for the Raspberry Pi using the ethernet device](https://github.com/Nvreformat/Etherboot)
* [Bare Metal Raspberry Pi](https://taylorpetrick.com/blog/post/bare-metal-pi-setup)
* [Baking Pi – Operating Systems Development](https://www.cl.cam.ac.uk/projects/raspberrypi/tutorials/os/)
* [Search for 'Raspberry' topic on Github](https://github.com/topics/raspberry-pi-3?l=c)
* [elinux: Raspberry Pi Programming](https://elinux.org/Raspberry_Pi_Programming) or [elinux: RPi Hub](https://elinux.org/RPi_Hub)
* [Stanford CS104e - An Experimental Course on Operating Systems](https://web.stanford.edu/class/cs140e/)
* [Computer Systems](http://cs107e.github.io/)
* [Build a Debian-based ARM64 system for Raspberry Pi 3](https://github.com/UMRnInside/RPi-arm64)
* [Learning operating system development using Linux kernel and Raspberry Pi ](https://github.com/s-matyukevich/raspberry-pi-os)
* [A port of FreeRTOS to the raspberry pi 2B. With USB+Ethernet+TCP/IP. ](https://github.com/Forty-Tw0/RaspberryPi-FreeRTOS)
* [64-bit Tiano Core UEFI for the Raspberry Pi 3](https://github.com/andreiw/RaspberryPiPkg)
* [CXCORE-RaspberryPi3-ubuntu-18.04-aarch64](https://github.com/chainsx/ubuntu64-rpi#cxcore-raspberrypi3-ubuntu-1804-aarch64--)

## Beaglebone

* [BeagleBone Black I2C References](https://datko.net/2013/11/03/bbb_i2c/)
* [Learning BeagleBone Python Programming](https://hub.packtpub.com/learning-beaglebone-python-programming/)

## Linux Programming

* [Writing device drivers in Linux](http://freesoftwaremagazine.com/articles/drivers_linux/)
* [YOLINUX Tutorials](http://www.yolinux.com/TUTORIALS/)
* [Linux driver programming](https://sites.google.com/site/embedded247/ddcourse)
* [Free training materials and conference presentations](https://bootlin.com/docs/)
* [eBook: Linux Drivers](https://sysplay.github.io/books/LinuxDrivers/book/index.html) or [Slides: Linux Drivers](https://sysplay.in/index.php?pagefile=linux_drivers)
* Communication: [OpenEmbedded](http://www.openembedded.org/wiki/Main_Page), 

## Assembly

* [GCC-Inline-Assembly-HOWTO](https://www.ibiblio.org/gferg/ldp/GCC-Inline-Assembly-HOWTO.html)
* [Assembly programming](https://courses.cs.washington.edu/courses/cse351/17sp/lectures/CSE351-L07-asm-I_17sp-ink.pdf)

## RTOS

* [ROS](http://www.ros.org/)
* [FreeRTOS](freertos.org)
* [FreeRTOS - Explaination](http://www.aosabook.org/en/freertos.html)
* [FreeRTOS API Reference Documentation](http://web.ist.utl.pt/~ist11993/FRTOS-API/index.html)
* [How to Write a Small RTOS](https://larrylisky.com/2012/07/14/how-to-create-a-small-rtos/)
* [RTOS From Scrach](https://github.com/RTOS-From-Scratch)
* [Writing a simple operating system from scratch](https://www.cs.bham.ac.uk/~exr/lectures/opsys/10_11/lectures/os-dev.pdf)
* [Free real-time operating system (RTOS) designed for deeply embedded applications](https://github.com/stateos/StateOS)
* [MPSoC FreeRTOS Development](http://www.wiki.xilinx.com/MPSoC+FreeRTOS+Development)
* [Atomthreads: Open Source RTOS](https://atomthreads.com/)
* [High performance motor control](https://github.com/madcowswe/ODrive)
* [MINIX3: Open source RTOS](http://www.minix3.org/)
* [30 Days make OS](https://github.com/yourtion/30dayMakeOS) --> [YOS](https://github.com/yourtion/YOS) @[Yannik](https://yannik520.github.io/)
* Communication: [OSDEV.org](https://wiki.osdev.org/Main_Page), [reddit/osdev](https://www.reddit.com/r/osdev/)
* [Real-time System Group](https://www.cs.york.ac.uk/rts/)
* [object-oriented C++ RTOS for microcontrollers](https://github.com/DISTORTEC/distortos)
* [RT-Thread is an open source IoT operating system from China.](https://github.com/RT-Thread/rt-thread)
* [How to create an OS from scratch ](https://github.com/cfenollosa/os-tutorial)
* [TetrOS is a small feature rich Tetris clone which is written in Assembly.](https://github.com/daniel-e/tetros)

## AUTOSAR

* [Trampoline is a static RTOS for small embedded systems.](https://github.com/TrampolineRTOS/trampoline)

## OS

* [ucLinux](http://www.uclinux.org/): The Embedded Linux/Microcontroller project is a port of Linux to systems without a Memory Management Unit (MMU).
* [Tizen](https://www.elinux.org/Tizen)

## Compiler

* [ARM Compiler - armasm User Guide](https://static.docs.arm.com/dui0801/i/DUI0801I_armasm_user_guide.pdf)

## Bootloader

* [Writing a boot loader in Assembly and C](https://www.codeproject.com/Articles/664165/Writing-a-boot-loader-in-Assembly-and-C-Part)
* [Writing a Bootloader Part 3](http://3zanders.co.uk/2017/10/18/writing-a-bootloader3/)

## Others

* [A practical approach to Kalman filter and how to implement it](http://blog.tkjelectronics.dk/2012/09/a-practical-approach-to-kalman-filter-and-how-to-implement-it/)
* [Embedded System programming](http://www.5square.in/): Diving into Syllabus for investigation.
* [ELC 2018 Presentations](https://elinux.org/ELC_2018_Presentations)
* [ARM Edition](https://sparkylinux.org/wiki/doku.php/sparky_arm): Sparky ARM Edition is a Sparky version created for a single board mini computer RaspberryPi. 
* [The gem5 Simulator](https://developer.arm.com/research/research-enablement/system-modeling) is a well-known sophisticated simulator used for computer system research at both architecture and micro-architecture levels. Main page is [here](http://gem5.org/Main_Page).
* [LineageOS Android Distribution](https://github.com/LineageOS)
* [The NoCAN platform](http://omzlo.com/articles/the-nocan-platform)
* [Realtime OS on Embedded Systems](http://socialledge.com/sjsu/index.php/Realtime_OS_on_Embedded_Systems)
* [These projects were produced in the five weeks of ECE 4760 each year. ](https://people.ece.cornell.edu/land/courses/ece4760/FinalProjects/)
* [Advanced fault backtrace library for ARM Cortex-M series MCU](https://github.com/armink/CmBacktrace)

## Tips & tricks

* [Awesome Cheat Sheets](https://github.com/mintisan/awesome-cheat-sheets/blob/master/README.md)
> Awesome Cheat Sheets for Developer Utility, like Git, Vim , Tmux, SublimeText, Markdown, Shell.

* [Vim Config for Reading Linux Kernel Source Code](https://github.com/mintisan/oh-my-vim)

## FAQ_Embedded

* [Boot section is removed (gcc, ld, ar, as)](https://www.embeddedrelated.com/showthread/lpc2000/47841-1.php)

## [Books for embedded system developers](http://www.ganssle.com/bkreviews.htm)
