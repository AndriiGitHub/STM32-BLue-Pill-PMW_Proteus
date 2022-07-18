# STM32-BLue-Pill-PMW_Proteus
STM32, Proteus
Library Installation :
Download or clone stm32 bluepill for proteus repository.
Open downloaded folder and copy BLUEPILL.IDX and BLUEPILL.LIB file from this folder.
Now open Proteus LIBRARY folder (check your proteus installation folder)
C:\Program Files (x86)\Labcenter Electronics\Proteus 8 Professional\DATA\LIBRARY

Now run proteus and open component Library.
Search for "STM32" or "BLUEPILL" and you can see your installed bluepill library.
Source code (Hex) :
Note: Select board as : STM32F103C6 in STM32CUBEMX or in STM32CUBEIDE. Only code compiled for STM32F103C6 is supported with this library.
Command to create hex file in CubeIDE:
arm-none-eabi-objcopy -O ihex ${ProjName}.elf ${ProjName}.hex

Перед початком роботи потрібно встановити необхідні бібліотеки BLUEPILL.IDX та BLUEPILL.LIB для Proteus за шляхом
C:\Program Files (x86)\Labcenter Electronics\Proteus 8 Professional\DATA\LIBRARY
При створенні проекту у CubeIDE необхідно обрати МК STM32F103C6
Для генерування hex файлу потрібно в налаштуваннях IDE додати команду
arm-none-eabi-objcopy -O ihex ${ProjName}.elf ${ProjName}.hex
