# NH Switch Guide

순정에서 Atmosphere까지, 스위치 커스텀 펌웨어 가이드

&nbsp;


### 홈브류(homebrew)란 무엇인가요?

!!! tip ""
    홈브류는 아마추어 개발자들이 만든 잠긴 시스템에서 구동되는 비공식 소프트웨어를 의미합니다.

    세이브 에딧 툴, 홈브류 게임, 에뮬레이터 등이 포함됩니다.

    스위치에서는 12.0.1 이하의 펌웨어에서 커스텀 펌웨어를 통해 홈브류를 구동할 수 있습니다.

### 커스텀 펌웨어(Custom Firmware)란 무엇인가요?

!!! tip ""
    Custom Firmware (“CFW”) is a piece software that modifies the system firmware.
    Atmosphere, for example, does this by running in the background and patching the OS on the fly.

    This allows one to extend the functionality of their system by giving homebrew higher levels of permission than most userland exploits and can be used to provide extra features for homebrew devs and users to take advantage of for various purposes, for instance, game modding using LayeredFS.

    CFW can be set up on any first-generation console on any version (but will require additional tools).

### What does this guide install?

!!! tip ""
    This guide has the end goal of taking a completely unmodified Switch from Stock Firmware to Atmosphere Custom Firmware.

    fusee-gelee is currently the best method of launching Custom Firmware that gives us nearly full control of the system. It utilizes a vulnerability in the bootROM of the first-generation Switch systems, allowing us to send any payload we want to the Switch's recovery mode, instead of only ones that Nintendo have authorized.

### What can I do with Custom Firmware?

!!! tip ""
    * Customize your HOME Menu with user-created themes and splash screens
    * Use “ROM hacks” for games that you own
    * Backup, edit, and restore saves for many games
    * Play games for older systems with various emulators, using RetroArch or other standalone emulators
    * Safely update to the latest system version without fear of losing access to homebrew

### What do I need to know before starting?

!!! tip ""
    Before beginning the guide, you must know the risks of Switch hacking: EVERY time you modify your system, there is always the potential for an UNRECOVERABLE brick. They’re rare but still a possibility so make sure you follow ALL directions EXACTLY.

    This guide will work on first-generation Switch consoles in all regions on firmware 12.0.1 or below.

    You will need one of the following in order to successfully follow this guide:

    - A USB-A to USB-C cable, and a PC
    - A USB-OTG cable, a USB-A to USB-C cable, and an Android device
		- This does not work on every android phone
    - A USB-C cable, and an Android device with a USB-C port
    - A Lightning-OTG adapter, a USB-A to USB-C cable, and a jailbroken iOS device
        - This method is not covered by the guide, but you can read more about it at [this website](https://mologie.github.io/nxboot/)


    You will also need a micro SD card that is at least 64 gigabytes or larger if you plan on following this guide through the emummc path, which is safer and strongly recommended. If you must use a smaller SD card, it is possible with the sysmmc path, but strongly not recommended.

    Finally, you will need a way to access Recovery Mode. (This will be further explained in the "Entering RCM section")

If everything goes according to plan, you will lose no data and end up with everything that you started with (games, Nintendo Account, saves, etc will be preserved).

Keep your device plugged in and charged throughout the entire process to avoid data loss or damage from an unexpected power-off.

Custom Firmware is not permanent with current methods, and will be unloaded upon rebooting the system.

It is advised that you read the entire guide from start to finish one or more times before actually running through the guide with your system.

&nbsp;

#### [Continue to Getting Started <i class="fa fa-arrow-circle-right fa-lg"></i>](user_guide/getting_started.md) 
