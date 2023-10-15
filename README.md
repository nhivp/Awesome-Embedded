# Awesome-Embedded

A curated list of awesome embedded resource.

Table of content

- [Awesome-Embedded](#awesome-embedded)
  - [Interview](#interview)
  - [Embedded Software Skill](#embedded-software-skill)
  - [Common](#common)
  - [MCU programming](#mcu-programming)
    - [Bare-metal programming (Don't need MCU)](#bare-metal-programming-dont-need-mcu)
    - [MSP430](#msp430)
    - [TM4C123](#tm4c123)
    - [MSP432](#msp432)
    - [STM32](#stm32)
    - [STM32F7](#stm32f7)
    - [STM8](#stm8)
    - [ESP8266](#esp8266)
  - [Raspberry](#raspberry)
  - [Beaglebone](#beaglebone)
  - [Linux Kernel and device driver development](#linux-kernel-and-device-driver-development)
  - [Assembly](#assembly)
  - [RTOS](#rtos)
  - [Automotive](#automotive)
  - [OS](#os)
  - [WindowCE](#windowce)
  - [Compiler](#compiler)
  - [Bootloader](#bootloader)
  - [Makefile](#makefile)
  - [Peripheral](#peripheral)
    - [Memory Protection Unit](#memory-protection-unit)
    - [USB](#usb)
  - [Others](#others)
  - [Embedded GUI Development](#embedded-gui-development)
  - [Machine Learning & AI on MCU](#machine-learning--ai-on-mcu)
  - [Utilities](#utilities)
  - [Tips & tricks](#tips--tricks)
- [Tech blogs](#tech-blogs)
  - [FAQ_Embedded](#faqembedded)
  - [Looking for more lists like this?](#looking-for-more-lists-like-this)
  - [BOOKs](#books)

## Interview

* [Questions which are frequently asked in an interview.](https://github.com/Embedded-Systems-Guide/interview-questions)
> On the way to be a full-stack embedded software engineer.

* [coding-interview-university](https://github.com/nhivp/coding-interview-university) - A complete computer science study plan to become a software engineer.

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
* [ARM Cortex M4 Blink Example (Linker Script)](http://robotics.mcmanis.com/src/arm-blink/linker-script.html)
* [A Sample Linker Script](http://hertaville.com/a-sample-linker-script.html)
* [Linking and Loading](http://www.iecc.com/linker/linker01.html)
* [Embedded Software _ Getting started](http://www2.thu.edu.tw/~emtools/DOE_project/NCCU/embedded%20system/ESD_06_GettingStarted.pdf)
* [How to convert from an armlink scatter file to a GNU ld linker script](https://www.mayrhofer.eu.org/node/24)
* [Using the GNU Linker](https://www.math.utah.edu/docs/info/ld_3.html)

## MCU programming

### Bare-metal programming (Don't need MCU)

* [Simplest bare metal program for ARM](https://balau82.wordpress.com/2010/02/14/simplest-bare-metal-program-for-arm/) ([table of content](https://balau82.wordpress.com/arm-emulation/))
* [Bare metal programming guide](github.com/cpq/bare-metal-programming-guide) - a detailed guide for beginners

### MSP430

* [MSP430-GCC](http://www.simplyembedded.org/tutorials/setting-up-a-virtual-machine/)
* [CS4101: Introduction to Embedded Systems](http://www.cs.nthu.edu.tw/~king/courses/cs4101/2016/cs4101.html) -  The course is designed around labs, using TI MSP430 LaunchPad and Arduino Uno to discuss concepts such as basic I/O, timing and clocking, interupt handling, serial communication, embedded operating systems, synchronization, etc.
* [msp430-template](https://github.com/uctools/msp430-template) - A template for MSP430 firmware.
* [MSP430 reference](https://students.cs.byu.edu/~clement/cs224/references/my_references.php)

### TM4C123

* [EmbeddedSystems.Playground](https://github.com/glennlopez/EmbeddedSystems.Playground/wiki/Periodic-SysTick-Interrupts)
* [Macros in TivaWare](https://sites.google.com/site/luiselectronicprojects/tutorials/tiva-tutorials/direct-register-access-notes/macros-in-tivaware)
* [Analog to Digital Conversion, Data Acquisition and Control](http://users.ece.utexas.edu/~valvano/Volume1/E-Book/C14_ADCdataAcquisition.htm)
* [Embedded Systems - Shape The World](http://users.ece.utexas.edu/~valvano/Volume1/E-Book/)
* [HowTo: Develop on the TI Tiva LaunchPad using Linux](http://chrisrm.com/howto-develop-on-the-ti-tiva-launchpad-using-linux/)
* [Linux command line build system to generate binaries for TM4C123 (ARM Cortex M4)](https://github.com/pitankar/TM4C)
* [The complete tutorial for Stellaris LaunchPad development with GNU/Linux (I)](http://kernelhacks.blogspot.com/2012/11/the-complete-tutorial-for-stellaris.html)
* [Getting Started with the TI Stellaris LaunchPad on Linux](https://www.jann.cc/2012/12/11/getting_started_with_the_ti_stellaris_launchpad_on_linux.html)
* [Embedded Systems with TM4C123 @Valvano](http://users.ece.utexas.edu/~valvano/arm/)
* [Create FreeRTOS Demo Project using the GCC Compiler](http://shukra.cedt.iisc.ernet.in/edwiki/EmSys:Create_freertos_on_tm4c123_CCS_Project)
* [Serial bootloader on TM4C12x Microcontroller](http://www.ti.com/lit/an/spma074a/spma074a.pdf)
* [Tivaware bootloader](http://www.ti.com/lit/ug/spmu301d/spmu301d.pdf)
* [Diagnosing Common Development Problems and Tips & Info for TM4C Devices](http://e2e.ti.com/support/microcontrollers/tiva_arm/f/908/t/374640)
* [FreeRTOS-GCC-tm4c123glx](https://github.com/nhivp/FreeRTOS-GCC-tm4c123glx) - A port of FreeRTOS to the Texas Instruments Tiva TM4C123GLX Launchpad.
* [Stellaris_TM4C123G_GCC_Template](https://github.com/AndoniV/Stellaris_TM4C123G_GCC_Template) - Texas Instruments template project for the TM4C123 series using GNU toolchain.
* [tm4c-gcc](https://github.com/martinjaros/tm4c-gcc) - TM4C123 GCC project template.
* [tivaapps](https://github.com/alexeicolin/tivaapps) - Example hello-world apps for Texas Instruments TI-RTOS for Tiva C using a Linux host
* [Drivers and examples](https://github.com/Mohammed-AhmedAF/ARM/tree/master/tiva-c) - Drivers for internal peripherals and external modules for Tiva C, examples of FreeRTOS features under development/FreeRTOS

### MSP432

* [Real-Time Bluetooth Networks - UTAustinX](https://github.com/monpeco/real_time_bn) - Learn the design fundamentals of a real-time operating system (RTOS) and how to build a Bluetooth network in this hands-on project-based course.

### STM32

* [STM32 bootloader](http://ciesie.com/post/stm32_bootloader/)
* [Tests to program STM32 Nucleo in C with GCC ARM embedded toolchain and libopencm3](https://github.com/balau/nucleo_tests)
* [A demo project of FreeRTOS running on a STM32F4 Discovery board.](https://github.com/wangyeee/STM32F4-FreeRTOS)
* [DFU Bootloader for STM32 chips](https://github.com/devanlai/dapboot)
* [Customizable Bootloader for STM32 microcontrollers.](https://github.com/akospasztor/stm32-bootloader)
* [Lightweight USB device Stack for STM32 microcontrollers](https://github.com/dmitrystu/libusb_stm32)
* [STM32 programming with Embedded GNU Compiler](https://github.com/rowol/stm32_discovery_arm_gcc)
* [A tiny portable 3D graphics lib for micro controllers (Oled display)](https://github.com/avem-labs/ol3d)
* [Getting started with the STM32F4-Discovery board using the EmBitz IDE](https://github.com/RoanFourie/STM32F4-DISCO-EMBITZ-Blinky)
* [libopencm3 and FreeRTOS projects using the STM32F103C8T6 MCU](https://github.com/ve3wwg/stm32f103c8t6)
* [A template for builting STM23F0 ARM projects with GCC](https://github.com/szczys/stm32f0-discovery-basic-template)
* [Open source flash program for STM32 using the ST serial bootloader](https://sourceforge.net/projects/stm32flash/)
* [stm32-hid-bootloader](https://github.com/bootsector/stm32-hid-bootloader) - Driverless USB HID bootloader and flashing tool for STM32F10X devices
* [stm32l1xx-template](https://github.com/uctools/stm32l1xx-template) - A template for building firmware for the STM32L1xx.
* [STM32F103C8 Examples](https://github.com/avislab/STM32F103)
* [stm32f103](https://github.com/trebisky/stm32f103) - Bare metal programming on a generic STM32F103c8 board
* [stm32_samples](https://github.com/dwelch67/stm32_samples)
* [stm32f4de example code](https://github.com/dwelch67/stm32f4d)
* [stm32f4xx with Rust at the HAL](https://apollolabsblog.hashnode.dev/series/stm32f4-embedded-rust-hal) - A series of tutorials for building STM32F4xx applications with Rust.
* [stm32-rf-scanner](https://github.com/gemesa/stm32-rf-scanner) - STM32 and nRF24L01+ based 2.4GHz RF scanner
* [stm32-dc-dc](https://github.com/gemesa/stm32-dc-dc) - STM32 based DC-DC converter
* [rustlink](https://github.com/gemesa/rustlink) - small set of Rust tools to program STM32 devices

### STM32F7
* [STM32F7 Series](https://www.st.com/en/microcontrollers/stm32f7-series.html?querycriteria=productId=SS1858)
* [STM32 eLinux](https://elinux.org/STM32)
* [STM32F7 os.mbed](https://os.mbed.com/platforms/ST-Discovery-F746NG/)

### STM8

* [stm8-bare-min](https://github.com/lujji/stm8-bare-min) - Tiny peripheral library for STM8S
* [stm8-bootloader](https://github.com/lujji/stm8-bootloader) - Serial bootloader for STM8S microcontrollers
* [stm8-multi-tasker](https://github.com/vsch/stm8-multi-tasker) - STM8-Multi-Tasker - Preemptive/Cooperative Round Robin Scheduler for STM8
* [Wolk STM8 stuff ](https://github.com/LonelyWolf/stm8)
* [STM8S001J3_tiny_board](https://github.com/HexRx/STM8S001J3_tiny_board) - A tiny dev board for STM8S001J3 MCU designed in KiCad.

### ESP8266

* [An open source bootloader for the ESP8266](https://github.com/raburton/rboot)
* [An esp8266 rom creation tool](https://github.com/raburton/esptool2)
* [Wi-FI ESP8266 learning journey](https://github.com/xuhongv/StudyInEsp8266)
* [Wi-FI ESP32 learning journey](https://github.com/xuhongv/StudyInEsp32)
* [Sming - ESP8266/ESP32 IoT Framework](https://github.com/SmingHub/Sming)


## Raspberry

* [Raspberry Pi Bare Metal](https://github.com/fordp2002/ArmCopro/wiki/Raspberry-Pi-Bare-Metal) & [related link](https://microeletroniki.wordpress.com/)
* [ChibiOS/RT on the Raspberry Pi](https://www.stevebate.net/chibios-rpi/GettingStarted.html)
* [Raspberry Pi ARM based bare metal examples](https://github.com/dwelch67/raspberrypi)
* [Bare metal Raspberry Pi 3 tutorials](https://github.com/bztsrc/raspi3-tutorial)
* [Open Projects: Raspberry, Beaglebone BSP](https://devel.rtems.org/wiki/Developer/OpenProjects)
* [A Real-Time Operating System on the Raspberry Pi](http://www.pebblebay.com/raspberry-pi-embedded/)
* [A port of FreeRTOS to the raspberry pi](https://github.com/jameswalmsley/RaspberryPi-FreeRTOS)
* [FreeRTOS Sucessfully Ported](https://www.raspberrypi.org/forums/viewtopic.php?f=72&t=22423)
* [Exploring AArch64 assembler - Raspberry](https://thinkingeek.com/2016/10/08/exploring-aarch64-assembler-chapter1/)
* [A bootloader for the Raspberry Pi using the ethernet device](https://github.com/Nvreformat/Etherboot)
* [Bare Metal Raspberry Pi](https://taylorpetrick.com/blog/post/bare-metal-pi-setup)
* [Bare Metal Programming in C](http://www.valvers.com/open-software/raspberry-pi/step01-bare-metal-programming-in-cpt1/)
* [Baking Pi – Operating Systems Development](https://www.cl.cam.ac.uk/projects/raspberrypi/tutorials/os/)
* [Search for 'Raspberry' topic on Github](https://github.com/topics/raspberry-pi-3?l=c)
* [elinux: Raspberry Pi Programming](https://elinux.org/Raspberry_Pi_Programming) or [elinux: RPi Hub](https://elinux.org/RPi_Hub)
* [Stanford CS104e - An Experimental Course on Operating Systems](https://web.stanford.edu/class/cs140e/)
* [Computer Systems](http://cs107e.github.io/)
* [Build a Debian-based ARM64 system for Raspberry Pi 3](https://github.com/UMRnInside/RPi-arm64)
* [Learning operating system development using Linux kernel and Raspberry Pi](https://github.com/s-matyukevich/raspberry-pi-os)
* [A port of FreeRTOS to the raspberry pi 2B. With USB+Ethernet+TCP/IP.](https://github.com/Forty-Tw0/RaspberryPi-FreeRTOS)
* [64-bit Tiano Core UEFI for the Raspberry Pi 3](https://github.com/andreiw/RaspberryPiPkg)
* [CXCORE-RaspberryPi3-ubuntu-18.04-aarch64](https://github.com/chainsx/ubuntu64-rpi#cxcore-raspberrypi3-ubuntu-1804-aarch64--)
* [Sample source: Baremetal source code for Raspberry](https://github.com/LdB-ECM/Raspberry-Pi)
* [Sample source: NarcOS - A bare metal ultralight kernel for Raspberry Pi 3](https://github.com/forkachild/NarcOS)
* [Sample source: FreeRTOS v9.0.0 port for Raspberry Pi 1](https://github.com/leodido99/RaspberryPi1-FreeRTOSv9.0.0)
* [Sample source: A bare-metal experiments with the RaspberryPi](https://github.com/majorviraj/my-os)
* [「BareMetalで遊ぶ Raspberry Pi」のプログラムです。](https://github.com/jitomesky/RPi_Micon_C85book)
* [UEFI for RaspberryPi2 and RaspberryPi3 based on Linaro EDK2](https://github.com/ms-iot/RPi-UEFI)
* [ARM-episodes](https://github.com/invictus1306/ARM-episodes) & [ARM exploitation for IoT](https://quequero.org/2017/07/arm-exploitation-iot-episode-1/)
* [ARM shellcode and exploit development - BSidesMunich 2018](https://github.com/invictus1306/Workshop-BSidesMunich2018)
* [64 bit Bare Metal Programming on RPI-3](https://archive.fosdem.org/2017/schedule/event/programming_rpi3/attachments/slides/1475/export/events/attachments/programming_rpi3/slides/1475/bare_metal_rpi3.pdf)
* [Raspberry Pi 3 Bare Metal](https://adamransom.github.io/posts/raspberry-pi-bare-metal-part-1.html)
* [Assembly code for Raspberry Pi](https://github.com/Alkesst/RPIAssembly)
* [A public Baremetal Raspberry Pi code](https://github.com/LdB-ECM/Raspberry-Pi)
* [Raspberry-Pi Bare Metal Tutorial](https://github.com/BrianSidebotham/arm-tutorial-rpi)
* [uCOS-II on Raspberry Pi](https://github.com/fmlab/ucos_RaspberryPi)
* [Porting uCOSII to the raspberry pi A+/B+/2B](https://github.com/mopplayer/uCOSII_RPi)
* [Bare-metal examples](https://github.com/mrvn/RaspberryPi-baremetal)
* [Bare-metal lab](https://github.com/tzuCarlos/RaspberryPi)
* [Exploring Raspberry Pi: Interfacing to the Real World with Embedded Linux {book}](https://www.wiley.com/en-us/Exploring+Raspberry+Pi%3A+Interfacing+to+the+Real+World+with+Embedded+Linux-p-9781119188681)
* [Exploring Raspberry Pi: Interfacing to the Real World with Embedded Linux {website}](http://exploringrpi.com/)

## Beaglebone

* [BeagleBone Black I2C References](https://datko.net/2013/11/03/bbb_i2c/)
* [Learning BeagleBone Python Programming](https://hub.packtpub.com/learning-beaglebone-python-programming/)
* [Simple implementation of an OS for the BeagleBoard C4 with ARMv7 A8 processor.](https://github.com/Oxydation/MinionOS)
* [Various projects that utilize low level hardware instructions to interface with leds, speaker output and joystick input.](https://github.com/travelln/beaglebone-projects)
* [Windows Embedded Compact BSP for TI's Beaglebone](https://github.com/dvescovi1/WECBeagleBone)
* [BBB-BareMetal](https://github.com/allexoll/BBB-BareMetal)- Works on the beaglebone black (bare metal)
* [Running a Baremetal Beaglebone Black](https://www.twosixlabs.com/running-a-baremetal-beaglebone-black-part-1/) & [Part 2](https://www.twosixlabs.com/running-a-baremetal-beaglebone-black-part-2/)
* [Bare Metal on the BeagleBone (Black and Green)](https://www.cs.sfu.ca/CourseCentral/433/bfraser/other/BareMetalGuide.pdf) & [link1](https://www.cs.sfu.ca/CourseCentral/433/bfraser/other/) + [Link2](https://www.cs.sfu.ca/CourseCentral/433/bfraser/weekly.html)
* [A tutorial on bare-metal [OS] development on the Texas Instruments BeagleBoard.](https://wiki.osdev.org/ARM_Beagleboard)
* [bare metal c project for beaglebone, ti sitara am335x](https://github.com/0xCA5A/kickstart/tree/master/beaglebone/bare_metal_hello_world)
* [Bare Metal Applications on OSD335x using U-Boot](https://octavosystems.com/app_notes/bare-metal-on-osd335x-using-u-boot/#_Toc382081430)
* [bbb-asm-demo](https://github.com/mvduin/bbb-asm-demo) - Extremely tiny baremetal application for BeagleBone Black
* [Beaglebone - Getting started with JTAG and CCS](https://beagleboard.org/static/beaglebone/latest/Docs/ccs-jtag-simple.htm)
* [BeagleBoardJTAG](https://elinux.org/BeagleBoardJTAG)
* [beaglebone_samples](https://github.com/dwelch67/beaglebone_samples)
* [FreeRTOS for BeagleBone Black](https://github.com/henfos/BBBFreeRTOS)

## Linux kernel and device driver development

* [Linux inside](https://github.com/0xAX/linux-insides) - A little bit about a linux kernel
* [Writing device drivers in Linux](http://freesoftwaremagazine.com/articles/drivers_linux/)
* [YOLINUX Tutorials](http://www.yolinux.com/TUTORIALS/)
* [Linux driver programming](https://sites.google.com/site/embedded247/ddcourse)
* [Free training materials and conference presentations](https://bootlin.com/docs/)
* [eBook: Linux Drivers](https://sysplay.github.io/books/LinuxDrivers/book/index.html) or [Slides: Linux Drivers](https://sysplay.in/index.php?pagefile=linux_drivers)
* [c-periphery](https://github.com/vsergeev/c-periphery) - A C library for peripheral I/O (GPIO, SPI, I2C, MMIO, Serial) in Linux.
* [OpenEmbedded](http://www.openembedded.org/wiki/Main_Page),
* [Linux driver practices ](https://github.com/starnight/DriverPractice)
* [Linux Kernel Exploitation](https://github.com/xairy/linux-kernel-exploitation) - A bunch of links related to Linux kernel exploitation
* [Linux Kernel Module Cheat](https://github.com/cirosantilli/linux-kernel-module-cheat)
* [Start linux kernel module development!](https://rayanfam.com/topics/start-linux-kernel-module-development/)
* [Minimal Linux Live](https://github.com/ivandavidov/minimal) - a tiny educational Linux distribution
* [low-level programming university #linux-kernel-and-device-driver](https://github.com/gurugio/lowlevelprogramming-university#linux-kernel-and-device-driver)

## Assembly

* [GCC-Inline-Assembly-HOWTO](https://www.ibiblio.org/gferg/ldp/GCC-Inline-Assembly-HOWTO.html)
* [Assembly programming](https://courses.cs.washington.edu/courses/cse351/17sp/lectures/CSE351-L07-asm-I_17sp-ink.pdf)

## RTOS

* [List of open source real-time operating systems](https://www.osrtos.com/)
* [ROS](http://www.ros.org/)
* [FreeRTOS](https://freertos.org/)
* [FreeRTOS - Explaination](http://www.aosabook.org/en/freertos.html)
* [FreeRTOS API Reference Documentation](http://web.ist.utl.pt/~ist11993/FRTOS-API/index.html)
* [How to Write a Small RTOS](https://larrylisky.com/2012/07/14/how-to-create-a-small-rtos/)
* [RTOS From Scrach](https://github.com/RTOS-From-Scratch)
* [mini-arm-os & qemu with a stm32](https://github.com/embedded2015/mini-arm-os) or [here](https://github.com/jserv/mini-arm-os) - Build a minimal multi-tasking OS kernel for ARM Cortex-M series from scratch
* [Writing a simple operating system from scratch](https://www.cs.bham.ac.uk/~exr/lectures/opsys/10_11/lectures/os-dev.pdf)
* [Free real-time operating system (RTOS) designed for deeply embedded applications](https://github.com/stateos/StateOS)
* [MPSoC FreeRTOS Development](http://www.wiki.xilinx.com/MPSoC+FreeRTOS+Development)
* [Atomthreads: Open Source RTOS](https://atomthreads.com/)
* [High performance motor control](https://github.com/madcowswe/ODrive)
* [MINIX3: Open source RTOS](http://www.minix3.org/)
* [30 Days make OS](https://github.com/yourtion/30dayMakeOS) --> [YOS](https://github.com/yourtion/YOS) @[Yannik](https://yannik520.github.io/)
* Community: [OSDEV.org](https://wiki.osdev.org/Main_Page), [reddit/osdev](https://www.reddit.com/r/osdev/)
* [Real-time System Group](https://www.cs.york.ac.uk/rts/)
* [object-oriented C++ RTOS for microcontrollers](https://github.com/DISTORTEC/distortos)
* [RT-Thread is an open source IoT operating system from China.](https://github.com/RT-Thread/rt-thread)
* [How to create an OS from scratch](https://github.com/cfenollosa/os-tutorial)
* [Sample Source: TetrOS is a small feature rich Tetris clone which is written in Assembly.](https://github.com/daniel-e/tetros)
* [Sample Source: RTOS for microcontrollers](https://github.com/jimtremblay/nOS)
* [Sample Source: A Powerful embedded RTOS for ARM Cortex M microcontrollers](https://github.com/StratifyLabs/StratifyOS)
* [Sample Source: An embedded operating system for ARM Cortex-M based microcontrollers](https://github.com/onkwon/yaos)
* [Sample Source: rnk is a RTOS targeting ARM architecture.](https://github.com/raphui/rnk)
* [Sample Source: RTOS-From-Scratch](https://github.com/RTOS-From-Scratch/RTOS-From-Scratch)
* [Sample Source: Embeded OS for PIC32MX270F256B](https://github.com/envzhu/kozos-pic)
* [How I ended up writing a new real-time kernel](https://dmitryfrank.com/articles/how_i_ended_up_writing_my_own_kernel)
* [Sample Source: TNeo - a well-formed and carefully tested preemptive real-time kernel for 16- and 32-bits MCUs](https://github.com/dimonomid/tneo)
* [yaos is an embedded operating system for Internet of Things(IoT) devices, specifically for a single-core processor without MMU virtualization.](https://github.com/onkwon/yaos)
* [RT-Thread for Raspberry Pi 2B ](https://github.com/BernardXiong/raspi2)
* [tock](https://github.com/tock/tock) - A secure embedded operating system for Cortex-M based microcontrollers.
* [AliOS-Things](https://github.com/alibaba/AliOS-Things) - AliOS Things released by Alibaba is an open-source implementation of operating system (OS) for Internet of Things (IoT).
* [CoRTOS](https://forum.43oh.com/topic/13151-cortos-an-open-source-minimalist-rtos/) & [CoRTOS Simple Cooperative RTOS](https://sourceforge.net/projects/cortos-simple/) - An open source minimalist RTOS.
* [µOS++ Reference](http://micro-os-plus.github.io/develop/references/)
* [TNKernel](http://www.tnkernel.com/index.html) - a compact and very fast real-time kernel for the embedded 32/16/8 bits microprocessors.
* [Femto OS](http://www.femtoos.org/news.html) - a very concise portable real time - preemptive operating system (RTOS) for embedded microcontrollers with minimal ram and flash, say 2KB .. 16KB flash and 128 .. 1024 bytes ram.

## Automotive

* [Sample Source: Trampoline is a static RTOS for small embedded systems.](https://github.com/TrampolineRTOS/trampoline) & [labs](http://www.irccyn.ec-nantes.fr/~bechenne/trampoline-labs/)
* [Sample source: An integration an example AUTOSAR project which every part in AUTOSAR (OS, RTE, BSW, MCAL) are collected from different open source.](https://github.com/leduynguyen/My_AUTOSAR_Project)
* [automotive software(OSEK & AUTOSAR) ](https://github.com/parai/as) - Because I am not powerful so I decided to develop tiny but smart part of automotive software based on open source, and create a general AUTOSAR & Automotive Software study environment.

## OS

* [ucLinux](http://www.uclinux.org/): The Embedded Linux/Microcontroller project is a port of Linux to systems without a Memory Management Unit (MMU).
* [Tizen](https://www.elinux.org/Tizen)
* [Bootstrap yourself to write an OS from scratch. A book for self-learner.](https://github.com/tuhdo/os01)
* [Kernel 101 – Let’s write a Kernel](https://arjunsreedharan.org/post/82710718100/kernel-101-lets-write-a-kernel)
* [The little book about OS development](https://littleosbook.github.io/)
* [TetrOS](https://github.com/daniel-e/tetros) - Tetris that fits into the boot sector.
* [Writing a Simple Operating System from Scratch](https://www.cs.bham.ac.uk/~exr/lectures/opsys/10_11/lectures/os-dev.pdf)
* [JamesM's kernel development tutorials](http://www.jamesmolloy.co.uk/tutorial_html/)
* [Bare Bones](https://wiki.osdev.org/Bare_Bones) - a simple kernel for 32-bit x86 and boot it.
* [Operating System Development Series](http://www.brokenthorn.com/Resources/OSDevIndex.html)
* [7 Steps to Writing a Simple Cooperative Scheduler](https://www.edn.com/7-steps-to-writing-a-simple-cooperative-scheduler/)
* [A simple OS kernel for research, teaching, and fun](https://github.com/dthain/basekernel)
* [Operating Systems C Term 2018](https://github.com/Mcdonoughd/CS3013)

## WindowCE

* [GuruCE Blog](https://guruce.com/blog)
* [Windows CE Base Team Blog](https://blogs.msdn.microsoft.com/ce_base/)
* [DevWinCE blog](http://devwince.blogspot.com/)
* [Windows Embedded Compact BSP for Raspberry Pi](https://archive.codeplex.com/?p=ceonpi)
* [Windows Embedded Board Support Package for BeagleBone](https://archive.codeplex.com/?p=beaglebonebsp)

## Compiler

* [ARM Compiler - armasm User Guide](https://static.docs.arm.com/dui0801/i/DUI0801I_armasm_user_guide.pdf)

## Bootloader

* [Writing a boot loader in Assembly and C](https://www.codeproject.com/Articles/664165/Writing-a-boot-loader-in-Assembly-and-C-Part)
* [Writing a Bootloader Part 3](http://3zanders.co.uk/2017/10/18/writing-a-bootloader3/)
* [A bootloader for ARM Cortex-M based microcontrollers](https://github.com/onkwon/yaboot)
* [OpenBLT](https://github.com/feaser/openblt) - an open source and portable bootloader for microcontrollers.
* [ARMv7M ELF loader ](https://github.com/martinribelotta/elfloader)
* [Writing a Bootloader Part 1](http://3zanders.co.uk/2017/10/13/writing-a-bootloader/)
* [can-bootloader](https://github.com/cvra/can-bootloader) - The bootloader used to flash our CAN-connected boards
* [Bootloaders 101](https://www.embedded.com/design/prototyping-and-development/4410233/1/Bootloaders-101--making-your-embedded-design-future-proof)
* Understand boot process: [link1](https://www.beningo.com/understanding-the-microcontroller-boot-process/), [link2](https://www.beningo.com/understanding-the-microcontroller-boot-process/), [link3](https://www.eevblog.com/forum/microcontrollers/copy-data-from-rom-to-ram-and-execute/)
* Keywords: *hello world bootloader*, *writing a bootloader from scratch*, *how to write a bootloader in assembly*, ...

## Makefile

* [Managing projects with GNU Make](http://uploads.mitechie.com/books/Managing_Projects_with_GNU_Make_Third_Edition.pdf)
* [GCC and Make](https://www3.ntu.edu.sg/home/ehchua/programming/cpp/gcc_make.html)

## Peripheral

### Memory Protection Unit

* [Building Hardware Components for Memory Protection of Applications on a Tiny Processor](https://carrv.github.io/2017/papers/oh-mpu-carrv2017.pdf)
* [KeyStone Architecture: Memory Protection Unit (MPU)](http://www.ti.com/lit/ug/sprugw5a/sprugw5a.pdf)

### USB

* [tinyusb](https://github.com/hathach/tinyusb) - An open source USB stack for a variety of Embedded Systems.

## Others

* [A practical approach to Kalman filter and how to implement it](http://blog.tkjelectronics.dk/2012/09/a-practical-approach-to-kalman-filter-and-how-to-implement-it/)
* [Embedded System programming](http://www.5square.in/): Diving into Syllabus for investigation.
* [ELC 2018 Presentations](https://elinux.org/ELC_2018_Presentations)
* [ARM Edition](https://sparkylinux.org/wiki/doku.php/sparky_arm): Sparky ARM Edition is a Sparky version created for a single board mini computer RaspberryPi.
* [The gem5 Simulator](https://developer.arm.com/research/research-enablement/system-modeling) is a well-known sophisticated simulator used for computer system research at both architecture and micro-architecture levels. Main page is [here](http://gem5.org/Main_Page).
* [LineageOS Android Distribution](https://github.com/LineageOS)
* [The NoCAN platform](http://omzlo.com/articles/the-nocan-platform)
* [Realtime OS on Embedded Systems](http://socialledge.com/sjsu/index.php/Realtime_OS_on_Embedded_Systems)
* [These projects were produced in the five weeks of ECE 4760 each year.](https://people.ece.cornell.edu/land/courses/ece4760/FinalProjects/)
* [Advanced fault backtrace library for ARM Cortex-M series MCU](https://github.com/armink/CmBacktrace)
* [mcu-starter-projects](https://github.com/ataradov/mcu-starter-projects) - Simple starter projects for bare-metal MCU development.
* [DirtyJTAG](https://github.com/jeanthom/DirtyJTAG) - JTAG adapter firmware for STM32F1
* [Generic_MCU_Software_Infrastructure](https://github.com/GorgonMeducer/Generic_MCU_Software_Infrastructure) - Provide necessary software infrastructure, service, macros to support some high level abstruct concept or paradigm, such as OOPC, FSM, delegate (event-driven) and etc.
* [apollo](https://github.com/ApolloAuto/apollo) - An open autonomous driving platform.
* * [A Development Environment for ARM TrustZone with GlobalPlatform Support](https://www.eit.lth.se/sprapport.php?uid=793)

## Embedded GUI Development
* [Embedded Wizard](https://www.embedded-wizard.de/) - Sophisticated GUI for Your Embedded Platform
* [lvgl](https://lvgl.io/) - Graphics library to create an embedded GUI with easy-to-use graphical elements, beautiful visual effects and low memory footprint. It offers anti-aliasing, opacity, and animations using only one frame buffer.

## Machine Learning & AI on MCU
* [nnom](https://github.com/majianjia/nnom) - A higher-level Neural Network library for microcontrollers.
* [nn4mp](https://github.com/correlllab/nn4mp)
* [Embedded Learning Library (ELL)](https://github.com/Microsoft/ELL) - Microsoft's library to deploy intelligent machine-learned models onto resource constrained platforms and small single-board computers.
* [Qualcomm Neural Processing SDK for AI](https://developer.qualcomm.com/software/qualcomm-neural-processing-sdk) - Libraries to developers run NN models on Snapdragon mobile platforms taking advantage of the CPU, GPU and/or DSP.
* [CMSIS NN](https://arm-software.github.io/CMSIS_5/NN/html/index.html) - A collection of efficient neural network kernels developed to maximize the performance and minimize the memory footprint of neural networks on Cortex-M processor cores.
* [ARM Compute Library](https://developer.arm.com/technologies/compute-library) - Set of optimized functions for image processing, computer vision, and machine learning.
* [uTensor](https://github.com/uTensor/uTensor) - AI inference library based on mbed (an RTOS for ARM chipsets) and TensorFlow.
* [EmbededAI](https://github.com/boralt/EmbeddedAI) - A library that provides elements of AI to C++ applications.
* [kann](https://github.com/attractivechaos/kann) - A lightweight C library for artificial neural networks.
* [m2cgen](https://github.com/BayesWitnesses/m2cgen) - A CLI tool which allows to transpile trained classic ML models into a native code of various programming languages with zero dependencies including C.

## Utilities

* [lm4tools](https://github.com/utzig/lm4tools)
* [mspdebug](https://github.com/dlbeer/mspdebug) - Debugging tool for MSP430 MCUs
* [pycs](https://github.com/deadsy/pycs) - Python Based ARM CoreSight Debug and Trace Tools

## Tips & tricks

* [Awesome Cheat Sheets](https://github.com/mintisan/awesome-cheat-sheets/blob/master/README.md)
> Awesome Cheat Sheets for Developer Utility, like Git, Vim , Tmux, SublimeText, Markdown, Shell.

* [Vim Config for Reading Linux Kernel Source Code](https://github.com/mintisan/oh-my-vim)
* [GNU GDB Debugger Command Cheat Sheet](http://www.yolinux.com/TUTORIALS/GDB-Commands.html)

# Tech blogs

* [What a C programmer should know about memory](http://marek.vavrusa.com/memory/)
* [What Every Programmer Should Know About Memory](https://people.freebsd.org/~lstewart/articles/cpumemory.pdf)
* [What Every C Programmer Should Know About Undefined Behavior ](http://blog.llvm.org/2011/05/what-every-c-programmer-should-know.html) [part 2](http://blog.llvm.org/2011/05/what-every-c-programmer-should-know_14.html) [part 3](http://blog.llvm.org/2011/05/what-every-c-programmer-should-know_21.html)
* [A Guide to Undefined Behavior in C and C++](https://blog.regehr.org/archives/213)
* [Software Engineering Takeaways](https://blog.regehr.org/archives/1594)
* [Embedsys weekly newsletter](https://embedsysweekly.com/)

## FAQ_Embedded

* [Boot section is removed (gcc, ld, ar, as)](https://www.embeddedrelated.com/showthread/lpc2000/47841-1.php)
* [What are .axf files?](https://stackoverflow.com/questions/17761328/what-are-axf-files)

## Looking for more lists like this?

* [awesome-c](https://github.com/uhub/awesome-c) - A curated list of awesome C frameworks, libraries and software.
* [A curated list of project-based tutorials in C](https://github.com/rby90/Project-Based-Tutorials-in-C)
* [Curated list of project-based tutorials](https://github.com/tuvtran/project-based-learning)
* [Curated list of awesome lists](https://github.com/sindresorhus/awesome)
* [A curated list of awesome Raspberry Pi tools, projects, images and resources](https://github.com/thibmaek/awesome-raspberry-pi)
* [Curated List of Self-Driving Cars and Autonomous Vehicles Resources](https://github.com/takeitallsource/awesome-autonomous-vehicles)
* [awesome-embedded-systems](https://github.com/embedded-boston/awesome-embedded-systems)
* [awesome-cheat-sheets](https://github.com/mintisan/awesome-cheat-sheets) - Awesome Cheat Sheets for Developer Utility, like Git, Vim, Tmux, Sublime Text, Markdown, Shell.
* [awesome-embedded-rust](https://github.com/rust-embedded/awesome-embedded-rust) - Curated list of resources for Embedded and Low-level development in the Rust programming languague.

## BOOKs

* [Mastering the Raspberry Pi](http://web.archive.org/web/20190713103510/http://mensshed-llandudno.co.uk/wp-content/uploads/Mastering%20the%20Raspberry%20Pi.pdf)
* [Modern C](http://web.archive.org/web/20190219172719/http://icube-icps.unistra.fr/img_auth.php/d/db/ModernC.pdf)
