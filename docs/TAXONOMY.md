# TAXONOMY — rtos-firmware-atlas

Sibling of [uefi-firmware-atlas](https://github.com/vulragrag-star/uefi-firmware-atlas). Same closed-loop stages and use-tags.

## Inclusion
RTOS source trees, samples, fuzzers, CVE trackers for Zephyr/FreeRTOS/ThreadX/NuttX/RIOT/RTEMS.

## Exclusion
OpenWrt/Linux IoT images, UEFI, Arduino sketches without an RTOS, MCU SVD-only toolchains without RTOS context (→ mcu atlas).

## Stages
spec | acquire | parse | static_re | emulate_fuzz | runtime_assess | offense_poc | defend_harden | vuln_intel | dataset | paper_map | lab_teaching

## Series
See [uefi docs/SERIES.md](https://github.com/vulragrag-star/uefi-firmware-atlas/blob/main/docs/SERIES.md).
