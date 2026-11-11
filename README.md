# Open-Source Contribution Portfolio

[![Zephyr RTOS](https://img.shields.io/badge/Zephyr_RTOS-Merged_upstream-003366?style=flat&logo=zephyrproject&logoColor=white)](https://github.com/zephyrproject-rtos/zephyr)
[![EDK II](https://img.shields.io/badge/EDK_II-Under_review-107C41?style=flat&logo=cplusplus&logoColor=white)](https://github.com/tianocore/edk2-platforms)
[![QEMU](https://img.shields.io/badge/QEMU-Under_review-FF6600?style=flat&logo=qemu&logoColor=white)](https://github.com/qemu/qemu)
[![OpenOCD](https://img.shields.io/badge/OpenOCD-Under_review-2E8B57?style=flat)](https://github.com/openocd-org/openocd)
![Views](https://komarev.com/ghpvc/?username=khaidox-upstream-contributions&label=Views&color=0e75b6&style=flat)

A portfolio of upstream contributions across systems infrastructure, RTOS, UEFI firmware, and hardware emulation for 64-bit ARM platforms (Allwinner H618 / Cortex-A53).

> **Contributor:** Khai Do (Official Zephyr RTOS Maintainer for Allwinner Platforms)<br>
> **GitHub:** [@khaidox](https://github.com/khaidox)

---

## 📌 Contribution Overview

| Project | Description | Commits | Status |
| :--- | :--- | :---: | :---: |
| **[Zephyr RTOS](https://github.com/zephyrproject-rtos/zephyr)** | Open-source real-time operating system (RTOS) for connected, resource-constrained devices | 7 | Merged upstream |
| **[EDK II / TianoCore](https://github.com/tianocore/edk2-platforms)** | Open-source UEFI firmware development framework | 7 | Under review |
| **[QEMU](https://github.com/qemu/qemu)** | Open-source system emulator and virtualizer | 8 | Under review |
| **[OpenOCD](https://github.com/openocd-org/openocd)** | Open-source tool for JTAG/SWD programming and on-chip debugging | 1 | Under review |

---

## 1. Zephyr RTOS

* **Repository:** [`zephyrproject-rtos/zephyr`](https://github.com/zephyrproject-rtos/zephyr)
* **Role:** Official Zephyr RTOS Maintainer for Allwinner Platforms
* **Description:** Open-source real-time operating system (RTOS) for connected, resource-constrained devices
* **Status:** Merged upstream

| Commit | Status | Title |
| :---: | :---: | :--- |
| [`12485ba4520`](https://github.com/zephyrproject-rtos/zephyr/commit/12485ba452036033faf43bc55d9bb707f18609ef) | Merged upstream | MAINTAINERS: add khaidox as maintainer to Allwinner Platforms |
| [`397656e6a2f`](https://github.com/zephyrproject-rtos/zephyr/commit/397656e6a2fa489c8acf3c3380a2138d7f32d3d9) | Merged upstream | dts: arm64: allwinner: Enable H618 GPIO support on Orange Pi Zero 2W |
| [`9ecdddd0ce1`](https://github.com/zephyrproject-rtos/zephyr/commit/9ecdddd0ce1dbaee7bd2f150c1dfa5bddcb5522d) | Merged upstream | boards: xunlong: opi_zero2w: add board image to documentation |
| [`c5ba1c95599`](https://github.com/zephyrproject-rtos/zephyr/commit/c5ba1c955991f70934147e4eefa2ca2db01c2d34) | Merged upstream | drivers: gpio: Add Allwinner H618 GPIO driver |
| [`cea1135d0be`](https://github.com/zephyrproject-rtos/zephyr/commit/cea1135d0bebe1ebf06c895f369327387ca283fb) | Merged upstream | boards: xunlong: add Orange Pi Zero 2W board support |
| [`7f3e05fd98b`](https://github.com/zephyrproject-rtos/zephyr/commit/7f3e05fd98b1baf614533769deb88224079c7214) | Merged upstream | dts: arm64: allwinner: add sun50i-h618 SoC dtsi |
| [`bdb73695d71`](https://github.com/zephyrproject-rtos/zephyr/commit/bdb73695d71ff44c15988d5b795d3ed462b3f68e) | Merged upstream | soc: arm64: allwinner: add sun50i_h618 SoC support |

---

## 2. EDK II / TianoCore

* **Repository:** [`tianocore/edk2-platforms`](https://github.com/tianocore/edk2-platforms)
* **Description:** Open-source UEFI firmware development framework for modern platforms
* **Status:** Under review

| Commit | Status | Title |
| :---: | :---: | :--- |
| `6f9c9d112b` | Under review | Silicon/Allwinner: Add support for Allwinner H618 SoC |
| `c8ae159352` | Under review | Silicon/Allwinner: Add AllwinnerRtcLib for H618 RTC controller |
| `34771d3c8b` | Under review | Silicon/Allwinner: Add OemMiscLib for H618 SMBIOS tables |
| `6aa9757b90` | Under review | Silicon/Allwinner: Add siddump UEFI Shell command for H618 SID |
| `835c621562` | Under review | Platform/OrangePi: Add OrangePiZero2W build configuration |
| `dacb3f40ba` | Under review | Platform/OrangePi: Add documentation for Orange Pi Zero 2W |
| `f611584c80` | Under review | CODEOWNERS: Add maintainer for Allwinner and OrangePi |

---

## 3. QEMU

* **Repository:** [`qemu/qemu`](https://github.com/qemu/qemu)
* **Description:** Open-source system emulator and virtualizer
* **Status:** Under review

| Commit | Status | Title |
| :---: | :---: | :--- |
| `97429ccf1c` | Under review | hw/arm/allwinner-h618: Add Allwinner H618 SoC emulation |
| `c115e6bb38` | Under review | hw/arm/orangepi-zero2w: Add Orange Pi Zero 2W machine |
| `fdbc6ea5da` | Under review | hw/misc/allwinner-sid: Separate ALLWINNER_SID config symbol |
| `0ffa46f505` | Under review | hw/misc/allwinner-sid: Support configurable eFuse capacity up to 512 bytes |
| `e6b717f93a` | Under review | hw/arm/allwinner-h618: Connect Allwinner SID controller |
| `22af83f304` | Under review | hw/sd/allwinner-sdhost: Separate ALLWINNER_SDHOST config symbol |
| `f14868004a` | Under review | hw/arm/allwinner-h618: Connect Allwinner SD/MMC host controller 0 |
| `76dd2468a0` | Under review | hw/arm/orangepi-zero2w: Wire up SD card and support firmware loading |

---

## 4. OpenOCD

* **Repository:** [`openocd-org/openocd`](https://github.com/openocd-org/openocd)
* **Description:** Open On-Chip Debugger for JTAG/SWD programming and on-chip debugging
* **Status:** Under review

| Commit | Status | Title |
| :---: | :---: | :--- |
| `f62c0f404` | Under review | tcl/target/allwinner_h618: Improve multi-core and SMP configuration |

