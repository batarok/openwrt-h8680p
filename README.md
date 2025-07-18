# OpenWrt Freedom

Custom OpenWrt firmware for **ZTE HG680P (Amlogic S905X)** and **x86_64** with OpenClash support.

---

## Features

- **Target:** meson64 or x86_64
- **Device Tree:** meson-gxl-s905x-p212.dtb
- **OpenClash** pre-installed
- **LuCI** web interface with SSL
- **Argon** themes

---

## Custome File

- OpenWRT Config:
  - inside config folder

- OpenWRT Version:
   - HG680P > openwrt-version-hg680p.txt
   - X86_64 > version-x86_64.txt

- OpenWRT Feeds:
  - feeds.conf.default

- OpenWRT Packages:
   - Include: 
     - HG680P > hg680p.include
     - X86_64 > x86_64.include
   - Exclude:
     - All: > packages.exclude

- OpenWRT Workflow:
  - inside .github/workflow folder

---

## How to Build

1. Open **Actions** menu.
2. Choose workflow:
   - [HG680P Workflow](https://github.com/batarok/openwrt-freedom/actions/workflows/hg680p.yaml)
   - [x86_64-bios Workflow](https://github.com/batarok/openwrt-freedom/actions/workflows/build-x86_64-bios.yaml)
   - [x86_64-uefi Workflow](https://github.com/batarok/openwrt-freedom/actions/workflows/build-x86_64-uefi.yaml)

---

## Credits

- [OpenWrt](https://openwrt.org/)
- [OpenClash](https://github.com/vernesong/OpenClash) by Vernesong
- [Argon Themes](https://github.com/jerrykuku/luci-theme-argon) by JerryK

---

## License

Free for personal use only. Redistribution is permitted free of charge, but not for commercial use.
See the LICENSE file for details.

---