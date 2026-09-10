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

## Status (crawl merge 2026-09-10)
- Tools: **136** (fringe flagged: **39**)
- Papers / vulns / datasets: **25** / **14** / **8**
- Seeds surveyed first (Zephyr awesomes thin; FreeRTOS/ThreadX/NuttX expanded via org trees): `data/seeds/SOURCES.md` · `docs/CRAWL_SUMMARY.md`

### Tool counts by stage

| Stage | n |
|---|---|
| acquire | 8 |
| defend_harden | 10 |
| emulate_fuzz | 14 |
| lab_teaching | 44 |
| offense_poc | 2 |
| paper_map | 4 |
| parse | 3 |
| runtime_assess | 13 |
| spec | 37 |
| static_re | 1 |
| **total** | **136** |


## Quick start
```bash
python scripts/validate_catalog.py
python scripts/render_catalogs.py
```

## License
Docs: CC BY 4.0. Scripts: MIT. Upstream projects keep their licenses.
