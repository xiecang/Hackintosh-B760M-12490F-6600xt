# Hackintosh-B760M-12490F-6600xt

![about](https://raw.githubusercontent.com/xiecang/Hackintosh-B760M-12490F-6600xt/master/images/about.png)

**Opencore Bootloader 0.9.2. Tested on Ventura 13.2.1**

## Introdution

You will have to [**generate a new SMIBIOS**](https://github.com/corpnewt/GenSMBIOS) before login to your iCloud account.

## Hardware Specs

- **Motherboard**: [MS-Terminator B760M D4](https://www.maxsun.com.cn/2023/0302/5916.html)
- **CPU**: [Intel® Core™ i5-12490F](https://www.intel.com/content/www/us/en/products/sku/134588/intel-core-i512490f-processor-20m-cache-up-to-4-60-ghz/specifications.html)
- **GPU**: [ASRock AMD Radeon RX 6600 XT Challenger ITX 8GB](https://www.asrock.com/Graphics-Card/AMD/Radeon%20RX%206600%20XT%20Challenger%20ITX%208GB/)
- **RAM**: 32GB DDR4 2666 ADATA
- **HDD**: WD Blue SN550 NVMe SSD 2T
- **Wi-Fi & Bluetooth**: BCM94360CD

## Working

- CPU Turbo Boost & SpeedStep
- Radeon™ RX 6600 XT
- Internal Speaker / Front panel headphone out / Back panel lineout
- USB Ports (rear USB 2.0 ports disabled due to macOS ports limit)
- LAN & Wireless Network
- Sleep & Wakeup
- Airdrop / Airplay / Handoff

## Not working

- Sidecar (needs T2 chip)
- DRM Content in Safari (needs T2 chip)

## UEFI Settings

Disabled

- Fast Boot
- VT-d
- CSM
- Intel SGX
- Intel Platform Trust
- CFG Lock
- Secure Boot
- Parallel Port
- Serial/COM Port

Enabled

- VT-x
- Above 4G decoding
- Hyper-Threading
- Execute Disable Bit
- EHCI/XHCI Hand-off
- Legacy RTC Device

## Changelog

**2023-05-14**

- update to Opencore 0.9.2
- tested on Ventura 13.2.1
- KEXTs up to date
- other minor updates
