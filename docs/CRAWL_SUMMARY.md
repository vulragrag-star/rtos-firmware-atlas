# RTOS tools crawl summary

Generated: 2026-09-10 16:13 CST (Asia/Shanghai)

## Totals
- In-scope catalog entries: **136** (success criterion ≥60; RTOS/MCU ≥40)
- Papers: **25** (criterion ≥20)
- Vulns: **14** (criterion ≥10)
- Datasets: **8** (criterion ≥5)
- Stars/last_push/license/language: live `gh api` metadata
- Seeds: golioth/awesome-zephyr-rtos, fkromer/awesome-zephyr, Technoculture/awesome-zephyr-rtos
- Expansion: gh search (zephyr, FreeRTOS, nuttx, threadx, RIOT-OS, RTEMS, freertos fuzzing, topic:rtos/zephyr) + WebSearch papers/CVEs
- Method: gh API / gh search / WebFetch only — **no repo clones**

## Counts by closed_loop_stage
| stage | count |
|-------|------:|
| spec | 37 |
| acquire | 8 |
| parse | 3 |
| static_re | 1 |
| emulate_fuzz | 14 |
| runtime_assess | 13 |
| offense_poc | 2 |
| defend_harden | 10 |
| paper_map | 4 |
| lab_teaching | 44 |
| **total** | **136** |

## Top 15 must-have tools

- **zephyr** (16466★) — `spec` — Zephyr RTOS primary tree. — https://github.com/zephyrproject-rtos/zephyr
- **FreeRTOS** (7780★) — `spec` — Classic FreeRTOS distribution (kernel+demos+libs). — https://github.com/FreeRTOS/FreeRTOS
- **FreeRTOS-Kernel** (4481★) — `spec` — FreeRTOS kernel-only repository. — https://github.com/FreeRTOS/FreeRTOS-Kernel
- **FreeRTOS-Plus-TCP** (214★) — `spec` — FreeRTOS+TCP stack (many historical CVEs). — https://github.com/FreeRTOS/FreeRTOS-Plus-TCP
- **threadx** (3524★) — `spec` — Eclipse ThreadX (ex Azure RTOS) kernel. — https://github.com/eclipse-threadx/threadx
- **RIOT** (5791★) — `spec` — RIOT OS for IoT. — https://github.com/RIOT-OS/RIOT
- **nuttx** (4025★) — `spec` — Apache NuttX POSIX-like RTOS. — https://github.com/apache/nuttx
- **rtems** (769★) — `spec` — RTEMS real-time OS (GitHub mirror). — https://github.com/RTEMS/rtems
- **renode** (2868★) — `emulate_fuzz` — Renode multi-node embedded/RTOS simulator. — https://github.com/renode/renode
- **mcuboot** (2098★) — `defend_harden` — MCUboot secure bootloader for MCUs. — https://github.com/mcu-tools/mcuboot
- **RTCON** (8★) — `emulate_fuzz` — RTCon context-adaptive RTOS function-level fuzzer (NDSS 2026). — https://github.com/kaist-hacking/RTCON
- **west** (366★) — `acquire` — West meta-tool for Zephyr workspaces. — https://github.com/zephyrproject-rtos/west
- **mynewt-core** (890★) — `spec` — Apache Mynewt RTOS core. — https://github.com/apache/mynewt-core
- **contiki-ng** (1525★) — `spec` — Contiki-NG IoT OS. — https://github.com/contiki-ng/contiki-ng
- **rt-thread** (12207★) — `spec` — RT-Thread IoT RTOS. — https://github.com/RT-Thread/rt-thread

## Exclusion notes (tempting misses)
- espressif/esp-idf — Primary ESP-IDF MCU framework → mcu-firmware-atlas (fence).
- micropython/micropython — Language VM; not an RTOS analysis tree → mcu/general.
- platformio/platformio-core — Generic embedded IDE core; not RTOS-specific.
- Indspl0it/RTOSploit — Repo 404 / unavailable at crawl time; mentioned in web index only.
- lvgl/lvgl — Standalone GUI toolkit; use zephyrproject-rtos/lvgl module if needed.
- firmadyne/firmadyne — Embedded Linux firmware emu → iot-firmware-atlas.
- tianocore/edk2 — UEFI → uefi-firmware-atlas.
- google/syzkaller — Linux kernel fuzzer → linux-kernel-atlas.
- Arduino-only blink sketches without RTOS — Fence: Arduino-only without RTOS OUT.
- OpenWrt / full Linux IoT images — Fence → iot-firmware-atlas.

## Fringe (included with notes)
- nhivp/Awesome-Embedded — Index; filter carefully.
- Mbed-TLS/mbedtls — Not RTOS-only; critical dependency.
- wasm-micro-runtime/wasm-micro-runtime — Portable runtime.
- ARMmbed/mbed-os — mbed CLI; large tree.
- zmkfirmware/zmk — west build; BLE keyboards.
- espressif/ESP8266_RTOS_SDK — ESP8266 toolchain.
- InfiniTimeOrg/InfiniTime — PineTime HW.
- ZSWatch/ZSWatch — Custom HW.
- wolfSSL/wolfssl — Build portable; not RTOS-only.
- aws/amazon-freertos — Deprecated; use FreeRTOS-LTS paths.
- SuperHouse/esp-open-rtos — ESP8266.
- whitecatboard/Lua-RTOS-ESP32 — ESP32.
- feilipu/Arduino_FreeRTOS_Library — Arduino IDE.
- mudita/MuditaOS — Specific HW.
- seemoo-lab/frankenstein — Specialized FW images.
- heliosproj/HeliOS — Limited boards.
- eclipse-threadx/guix — Optional component.
- eclipse-threadx/getting-started — Archived.
- purduesigbots/pros — VEX HW.
- tylerwhall/zephyr-rust — May lag official.
- open-vela/nuttx — Compare to apache/nuttx.
- swedishembedded/control — C library.
- PX4/NuttX — Flight-stack coupling.
- project-ocre/ocre-runtime — Zephyr module.
- koenvervloesem/openhaystack-zephyr — BLE HW.

## Scope reminders
- **IN**: Zephyr, FreeRTOS, ThreadX/AzureRTOS, NuttX, RIOT, RTEMS (+ Contiki-NG/Mynewt/ChibiOS/RT-Thread as RTOS trees); RTOS fuzzers (RTCon), MCUboot, Renode, west, +TCP CVE trackers.
- **OUT**: Full Linux IoT images, UEFI/EDK2, Arduino-only without RTOS, ESP-IDF-as-primary MCU (→ mcu-firmware-atlas), syzkaller (→ linux-kernel-atlas).

## Gaps
- Dedicated FreeRTOS/ThreadX/NuttX awesome lists remain thin (noted in seeds/SOURCES.md).
- Public RTOSploit repo was 404 at crawl time; cannot verify stars/license.
- HOEDUR/SFuzz++ artifacts not all mirrored as first-class GH tools in catalog (paper-linked).
- RTEMS canonical forge is GitLab; GitHub is mirror-only (stars understate activity).
- Few open offense_poc repos beyond CVE-2021-3625 and Contiki-NG attacks (research often private).
- Dataset scarcity: Heap-of-Chaos is behind IEEE DataPort; more public RTOS firmware corpora needed.
- static_re stage sparse vs UEFI atlas (few RTOS-specific Ghidra/IDA loaders; often generic MCU tools → mcu atlas).
- Rate-limit interrupted some late gh search queries (HeliOS/embOS/uC-OS); covered via direct repo API + known orgs.

## Smoke notes
- Crawl is metadata + curated classification; in-VM smoke of lab-usable subset not executed this pass.
- Practical starters: Zephyr west+QEMU/native_sim, FreeRTOS POSIX/QEMU demos, Renode Zephyr/RTEMS scripts, MCUboot samples, RTCON Docker (large).
