# rtos-firmware-atlas

Living map of **RTOS firmware** research (Zephyr, FreeRTOS, ThreadX, NuttX, …) — closed-loop taxonomy.

Sibling of [`uefi-firmware-atlas`](https://github.com/vulragrag-star/uefi-firmware-atlas) / [`oss-atlas`](https://github.com/vulragrag-star/oss-atlas).

## Why another list?
We first survey existing awesome/index repos (see `data/seeds/SOURCES.md`), then build a **machine-readable closed-loop atlas** that those lists are not: JSONL schema, use-tags, setting book, smoke notes, explicit domain fences.

## Inclusion / exclusion
- **IN:** RTOS source trees, samples, fuzzers, CVE trackers for Zephyr/FreeRTOS/ThreadX/NuttX/RIOT/RTEMS.
- **OUT:** OpenWrt/Linux IoT images, UEFI, Arduino sketches without an RTOS, MCU SVD-only toolchains without RTOS context (→ mcu atlas).

## Closed-loop map
See [`docs/MAP.md`](docs/MAP.md), [`docs/TAXONOMY.md`](docs/TAXONOMY.md), [`docs/SETTING.md`](docs/SETTING.md), [`docs/SMOKE.md`](docs/SMOKE.md).

## Status (bootstrap 2026-09-10)
- Seed survey recorded; core tools JSONL: **6** (crawl expansion in flight)
- Papers/vulns/datasets: filling via multi-agent crawl

## Quick start
```bash
python scripts/validate_catalog.py
python scripts/render_catalogs.py
```

## License
Docs: CC BY 4.0. Scripts: MIT. Upstream projects keep their licenses.
