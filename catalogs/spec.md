# spec

_37 entries_

- **[zephyr](https://github.com/zephyrproject-rtos/zephyr)** ★16466 — Zephyr RTOS primary tree.  
  tags: `reference-impl, lab-usable, paper-repro, daily-ops`  
  smoke: west build samples on VM/QEMU.

- **[rt-thread](https://github.com/RT-Thread/rt-thread)** ★12207 — RT-Thread IoT RTOS.  
  tags: `reference-impl, lab-usable, paper-repro`  
  smoke: Simulator/QEMU paths.

- **[FreeRTOS](https://github.com/FreeRTOS/FreeRTOS)** ★7780 — Classic FreeRTOS distribution (kernel+demos+libs).  
  tags: `reference-impl, lab-usable, daily-ops`  
  smoke: POSIX/QEMU demos.

- **[RIOT](https://github.com/RIOT-OS/RIOT)** ★5791 — RIOT OS for IoT.  
  tags: `reference-impl, lab-usable, paper-repro`  
  smoke: native/board samples.

- **[mbed-os](https://github.com/ARMmbed/mbed-os)** ★4873 — Arm Mbed OS (includes RTOS).  
  tags: `reference-impl, lab-usable`  
  smoke: mbed CLI; large tree.

- **[FreeRTOS-Kernel](https://github.com/FreeRTOS/FreeRTOS-Kernel)** ★4481 — FreeRTOS kernel-only repository.  
  tags: `reference-impl, lab-usable, paper-repro`  
  smoke: Submodule into app.

- **[nuttx](https://github.com/apache/nuttx)** ★4025 — Apache NuttX POSIX-like RTOS.  
  tags: `reference-impl, lab-usable, paper-repro`  
  smoke: Build on VM.

- **[ESP8266_RTOS_SDK](https://github.com/espressif/ESP8266_RTOS_SDK)** ★3568 — ESP8266 FreeRTOS-based SDK.  
  tags: `reference-impl, lab-usable`  
  smoke: ESP8266 toolchain.

- **[threadx](https://github.com/eclipse-threadx/threadx)** ★3524 — Eclipse ThreadX (ex Azure RTOS) kernel.  
  tags: `reference-impl, lab-usable, paper-repro`  
  smoke: Build samples; check license notes.

- **[amazon-freertos](https://github.com/aws/amazon-freertos)** ★2530 — DEPRECATED Amazon FreeRTOS (IoT) distribution.  
  tags: `reference-impl`  
  smoke: Deprecated; use FreeRTOS-LTS paths.

- **[esp-open-rtos](https://github.com/SuperHouse/esp-open-rtos)** ★1583 — Open FreeRTOS-based ESP8266 framework.  
  tags: `reference-impl, lab-usable`  
  smoke: ESP8266.

- **[contiki-ng](https://github.com/contiki-ng/contiki-ng)** ★1525 — Contiki-NG IoT OS.  
  tags: `reference-impl, lab-usable, paper-repro`  
  smoke: native/cooja sims.

- **[Lua-RTOS-ESP32](https://github.com/whitecatboard/Lua-RTOS-ESP32)** ★1330 — Lua RTOS for ESP32.  
  tags: `lab-usable`  
  smoke: ESP32.

- **[mynewt-nimble](https://github.com/apache/mynewt-nimble)** ★893 — Apache NimBLE Bluetooth stack (Mynewt).  
  tags: `reference-impl, lab-usable, paper-repro`  
  smoke: BLE labs.

- **[mynewt-core](https://github.com/apache/mynewt-core)** ★890 — Apache Mynewt RTOS core.  
  tags: `reference-impl, lab-usable`  
  smoke: newt tool builds.

- **[ChibiOS](https://github.com/ChibiOS/ChibiOS)** ★863 — ChibiOS/RT embedded RTOS mirror.  
  tags: `reference-impl, lab-usable`  
  smoke: SVN mirror on GH.

- **[rtems](https://github.com/RTEMS/rtems)** ★769 — RTEMS real-time OS (GitHub mirror).  
  tags: `reference-impl, lab-usable, paper-repro`  
  smoke: Mirror; prefer gitlab.rtems.org for latest.

- **[CMSIS-FreeRTOS](https://github.com/ARM-software/CMSIS-FreeRTOS)** ★646 — CMSIS-RTOS v2 adaptation of FreeRTOS.  
  tags: `reference-impl, lab-usable`  
  smoke: With CMSIS packs.

- **[freertos-addons](https://github.com/michaelbecker/freertos-addons)** ★488 — Community FreeRTOS add-ons (C++ wrappers etc).  
  tags: `lab-usable, reference-impl`  
  smoke: With FreeRTOS.

- **[nuttx-apps](https://github.com/apache/nuttx-apps)** ★464 — Apache NuttX applications collection.  
  tags: `reference-impl, lab-usable`  
  smoke: Build with nuttx.

- **[sdk-zephyr](https://github.com/nrfconnect/sdk-zephyr)** ★437 — Nordic NCS downstream of Zephyr.  
  tags: `reference-impl, daily-ops`  
  smoke: Needs NCS west manifest.

- **[HeliOS](https://github.com/heliosproj/HeliOS)** ★413 — HeliOS embedded OS project.  
  tags: `reference-impl, lab-usable`  
  smoke: Limited boards.

- **[guix](https://github.com/eclipse-threadx/guix)** ★405 — ThreadX GUIX embedded GUI.  
  tags: `reference-impl`  
  smoke: Optional component.

- **[netxduo](https://github.com/eclipse-threadx/netxduo)** ★320 — ThreadX NetX Duo TCP/IP stack.  
  tags: `reference-impl, paper-repro`  
  smoke: Pairs with ThreadX.

- **[usbx](https://github.com/eclipse-threadx/usbx)** ★229 — ThreadX USBX USB host/device stack.  
  tags: `reference-impl`  
  smoke: Needs USB-capable board/QEMU.

- **[FreeRTOS-Plus-TCP](https://github.com/FreeRTOS/FreeRTOS-Plus-TCP)** ★214 — FreeRTOS+TCP stack (many historical CVEs).  
  tags: `reference-impl, lab-usable, paper-repro`  
  smoke: Build with kernel; fuzz target.

- **[nuttx](https://github.com/open-vela/nuttx)** ★193 — open-vela NuttX fork.  
  tags: `reference-impl`  
  smoke: Compare to apache/nuttx.

- **[NuttX](https://github.com/PX4/NuttX)** ★172 — PX4-patched NuttX for flight stack.  
  tags: `reference-impl`  
  smoke: Flight-stack coupling.

- **[levelx](https://github.com/eclipse-threadx/levelx)** ★153 — ThreadX LevelX flash wear leveling.  
  tags: `reference-impl`  
  smoke: Pairs with FileX.

- **[filex](https://github.com/eclipse-threadx/filex)** ★63 — ThreadX FileX FAT filesystem.  
  tags: `reference-impl`  
  smoke: Lab with ThreadX.

- **[littlefs](https://github.com/zephyrproject-rtos/littlefs)** ★19 — littlefs module for Zephyr.  
  tags: `reference-impl`  
  smoke: FS labs.

- **[fatfs](https://github.com/zephyrproject-rtos/fatfs)** ★18 — FatFs module for Zephyr.  
  tags: `reference-impl`  
  smoke: FS labs.

- **[libmetal](https://github.com/zephyrproject-rtos/libmetal)** ★17 — libmetal HAL (Zephyr module).  
  tags: `reference-impl`  
  smoke: With open-amp.

- **[canopennode](https://github.com/zephyrproject-rtos/canopennode)** ★13 — CANopenNode module for Zephyr.  
  tags: `reference-impl`  
  smoke: CAN HW.

- **[open-amp](https://github.com/zephyrproject-rtos/open-amp)** ★13 — OpenAMP remoteproc/RPMsg (Zephyr module).  
  tags: `reference-impl`  
  smoke: Multi-core boards.

- **[zbus](https://github.com/zephyr-bus/zbus)** ★11 — Zephyr message bus (zbus).  
  tags: `lab-usable, reference-impl`  
  smoke: Zephyr module.

- **[sof](https://github.com/zephyrproject-rtos/sof)** ★4 — Sound Open Firmware (Zephyr module).  
  tags: `reference-impl`  
  smoke: Specialized audio DSPs.
