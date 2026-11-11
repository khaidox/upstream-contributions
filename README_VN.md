# Hồ Sơ Đóng Góp Mã Nguồn Mở

[![Zephyr RTOS](https://img.shields.io/badge/Zephyr_RTOS-Đã_Tích_Hợp_Upstream-003366?style=flat&logo=zephyrproject&logoColor=white)](https://github.com/zephyrproject-rtos/zephyr)
[![EDK II](https://img.shields.io/badge/EDK_II-Đang_Được_Review-107C41?style=flat&logo=cplusplus&logoColor=white)](https://github.com/tianocore/edk2-platforms)
[![QEMU](https://img.shields.io/badge/QEMU-Đang_Được_Review-FF6600?style=flat&logo=qemu&logoColor=white)](https://github.com/qemu/qemu)
[![OpenOCD](https://img.shields.io/badge/OpenOCD-Đang_Được_Review-2E8B57?style=flat)](https://github.com/openocd-org/openocd)
![Views](https://komarev.com/ghpvc/?username=khaidox-upstream-contributions&label=Lượt_Xem&color=0e75b6&style=flat)

Hồ sơ các đóng góp upstream trong lĩnh vực hạ tầng hệ thống, RTOS, firmware UEFI và giả lập phần cứng trên nền tảng ARM64 (Allwinner H618 / Cortex-A53).

> **Người đóng góp:** Khai Do — Maintainer chính thức của Zephyr RTOS cho nền tảng Allwinner<br>
> **GitHub:** [@khaidox](https://github.com/khaidox)

---

## 📌 Tổng Quan Đóng Góp

| Dự án | Mô tả dự án | Số Commit | Trạng thái |
| :--- | :--- | :---: | :---: |
| **[Zephyr RTOS](https://github.com/zephyrproject-rtos/zephyr)** | Hệ điều hành thời gian thực mã nguồn mở dành cho các thiết bị nhúng kết nối mạng và có tài nguyên hạn chế | 7 | Đã tích hợp upstream |
| **[EDK II / TianoCore](https://github.com/tianocore/edk2-platforms)** | Framework phát triển firmware UEFI mã nguồn mở | 7 | Đang được review |
| **[QEMU](https://github.com/qemu/qemu)** | Phần mềm mã nguồn mở dùng để giả lập và ảo hóa hệ thống | 8 | Đang được review |
| **[OpenOCD](https://github.com/openocd-org/openocd)** | Công cụ mã nguồn mở để nạp chương trình và gỡ lỗi trên chip qua JTAG/SWD | 1 | Đang được review |

---

## 1. Zephyr RTOS

* **Kho lưu trữ:** [`zephyrproject-rtos/zephyr`](https://github.com/zephyrproject-rtos/zephyr)
* **Vai trò:** Maintainer chính thức của Zephyr RTOS cho nền tảng Allwinner
* **Mô tả dự án:** Hệ điều hành thời gian thực mã nguồn mở dành cho các thiết bị nhúng kết nối mạng và có tài nguyên hạn chế
* **Trạng thái:** Đã tích hợp upstream

| Commit | Trạng thái | Tiêu đề Commit |
| :---: | :---: | :--- |
| [`12485ba4520`](https://github.com/zephyrproject-rtos/zephyr/commit/12485ba452036033faf43bc55d9bb707f18609ef) | Đã tích hợp upstream | MAINTAINERS: add khaidox as maintainer to Allwinner Platforms |
| [`397656e6a2f`](https://github.com/zephyrproject-rtos/zephyr/commit/397656e6a2fa489c8acf3c3380a2138d7f32d3d9) | Đã tích hợp upstream | dts: arm64: allwinner: Enable H618 GPIO support on Orange Pi Zero 2W |
| [`9ecdddd0ce1`](https://github.com/zephyrproject-rtos/zephyr/commit/9ecdddd0ce1dbaee7bd2f150c1dfa5bddcb5522d) | Đã tích hợp upstream | boards: xunlong: opi_zero2w: add board image to documentation |
| [`c5ba1c95599`](https://github.com/zephyrproject-rtos/zephyr/commit/c5ba1c955991f70934147e4eefa2ca2db01c2d34) | Đã tích hợp upstream | drivers: gpio: Add Allwinner H618 GPIO driver |
| [`cea1135d0be`](https://github.com/zephyrproject-rtos/zephyr/commit/cea1135d0bebe1ebf06c895f369327387ca283fb) | Đã tích hợp upstream | boards: xunlong: add Orange Pi Zero 2W board support |
| [`7f3e05fd98b`](https://github.com/zephyrproject-rtos/zephyr/commit/7f3e05fd98b1baf614533769deb88224079c7214) | Đã tích hợp upstream | dts: arm64: allwinner: add sun50i-h618 SoC dtsi |
| [`bdb73695d71`](https://github.com/zephyrproject-rtos/zephyr/commit/bdb73695d71ff44c15988d5b795d3ed462b3f68e) | Đã tích hợp upstream | soc: arm64: allwinner: add sun50i_h618 SoC support |

---

## 2. EDK II / TianoCore

* **Kho lưu trữ:** [`tianocore/edk2-platforms`](https://github.com/tianocore/edk2-platforms)
* **Mô tả dự án:** Framework phát triển firmware UEFI mã nguồn mở cho các nền tảng hiện đại
* **Trạng thái:** Đang được review

| Commit | Trạng thái | Tiêu đề Commit |
| :---: | :---: | :--- |
| `6f9c9d112b` | Đang được review | Silicon/Allwinner: Add support for Allwinner H618 SoC |
| `c8ae159352` | Đang được review | Silicon/Allwinner: Add AllwinnerRtcLib for H618 RTC controller |
| `34771d3c8b` | Đang được review | Silicon/Allwinner: Add OemMiscLib for H618 SMBIOS tables |
| `6aa9757b90` | Đang được review | Silicon/Allwinner: Add siddump UEFI Shell command for H618 SID |
| `835c621562` | Đang được review | Platform/OrangePi: Add OrangePiZero2W build configuration |
| `dacb3f40ba` | Đang được review | Platform/OrangePi: Add documentation for Orange Pi Zero 2W |
| `f611584c80` | Đang được review | CODEOWNERS: Add maintainer for Allwinner and OrangePi |

---

## 3. QEMU

* **Kho lưu trữ:** [`qemu/qemu`](https://github.com/qemu/qemu)
* **Mô tả dự án:** Phần mềm giả lập hệ thống và ảo hóa mã nguồn mở
* **Trạng thái:** Đang được review

| Commit | Trạng thái | Tiêu đề Commit |
| :---: | :---: | :--- |
| `97429ccf1c` | Đang được review | hw/arm/allwinner-h618: Add Allwinner H618 SoC emulation |
| `c115e6bb38` | Đang được review | hw/arm/orangepi-zero2w: Add Orange Pi Zero 2W machine |
| `fdbc6ea5da` | Đang được review | hw/misc/allwinner-sid: Separate ALLWINNER_SID config symbol |
| `0ffa46f505` | Đang được review | hw/misc/allwinner-sid: Support configurable eFuse capacity up to 512 bytes |
| `e6b717f93a` | Đang được review | hw/arm/allwinner-h618: Connect Allwinner SID controller |
| `22af83f304` | Đang được review | hw/sd/allwinner-sdhost: Separate ALLWINNER_SDHOST config symbol |
| `f14868004a` | Đang được review | hw/arm/allwinner-h618: Connect Allwinner SD/MMC host controller 0 |
| `76dd2468a0` | Đang được review | hw/arm/orangepi-zero2w: Wire up SD card and support firmware loading |

---

## 4. OpenOCD

* **Kho lưu trữ:** [`openocd-org/openocd`](https://github.com/openocd-org/openocd)
* **Mô tả dự án:** Công cụ mã nguồn mở để nạp chương trình và gỡ lỗi trên chip qua JTAG/SWD
* **Trạng thái:** Đang được review

| Commit | Trạng thái | Tiêu đề Commit |
| :---: | :---: | :--- |
| `f62c0f404` | Đang được review | tcl/target/allwinner_h618: Improve multi-core and SMP configuration |
