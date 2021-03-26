# pmps
Learning material and examples for course AR207 at FE Tuzla
# Software requirements
There are two approaches that can be used for compiling the firmware:
1. Using the Makefile
2. Using the STMCubeIDE application (https://www.st.com/en/development-tools/stm32cubeide.html)

Provided examples are equipped with dedicated Makefile and STMCubeIDE project file. This means that any example can be compiled using the Makefile or STMCubeIDE. 

If you get the following issue while trying to run the code: "Could not determine GDB version using command: arm-none-eabi-gdb --version",
you are probably missing libncurses5 dependency which can easily be installed by running `sudo apt-get install libncurses5`.

# Hardware requirements
For this course we will need following components:
- STM32F407 Disco Board (https://www.st.com/en/evaluation-tools/stm32f4discovery.html)
- USB 2.0 to TTL UART Serial Converter CP2102 (https://www.ebay.com/itm/1PCS-6Pin-USB-2-0-to-TTL-UART-Serial-Converter-CP2102-STC-Replace-Ft232/284022352349?hash=item42210d29dd:g:1y4AAOSwLTZfbBhs)
- Wire jumpers [MM,FF,MF] (https://www.ebay.com/itm/40PCS-20cm-2-54MM-FF-FM-MM-Dupont-wire-jumper-cables-male-to-female-For-Arduino/312724733910?hash=item48cfd8bfd6:g:05sAAOSwlbZdSZ6E)
