## ASUS ROG Strix B460-i

![image-20201202160801867](https://w-md.imzsy.design/Hackintosh-Info.png)

## Hardware

- **Motherboard:** Asus ROG Strix B460-I
  - Ethernet: Intel® i219-V 1Gb Ethernet
  - Audio Codec: Realtek ALCS1220A (Layout 7)
  - Wireless: Intel® Wi-Fi 6 AX200
- **CPU:** Intel Core i7 10700
- **dGPU:** AMD Radeon RX 6600 XT 8 GB
- **RAM:** Corsair Vengeance RGB PRO 16GB 2x8GB DDR4 3000Mhz
- **Storage:** Samsung SSD 970 EVO NVMe M.2（500GB）
  - Samsung SSD 860 EVO SATA III（500GB）
- **WiFi & Bluetooth:** BCM94352z(DW1560)

## GPU Performance
### Geekbench
- Metal  : 83111
- OpenCL : 67742

## Software

- **OS:** macOS Monterey 12.1 
- **Bootloader:** OpenCore 0.7.6

## BIOS Settings

**Disabled:**

- Fast Boot
- VT-d
- CSM
- Intel SGX
- CFG Lock (No option in BIOS, Asus B460 motherboards are factory unlocked)

**Enabled:**

- VT-x
- Above 4G decoding
- Hyper-Threading
- Execute Disable Bit
- EHCI/XHCI Hand-off
- OS type: Windows 8.1/10 UEFI Mode
- DVMT Pre-Allocated (iGPU Memory): 64MB

## What's working

-  Intel UHD630 (iGPU)
-  AMD Radeon RX 6600 XT (dGPU)
-  Restart/Shutdown
-  Sleep/Wake
-  Power Management (Native support)
-  WiFi & Bluetooth (BCM94352z)
-  USB

## Issues

### Color banding

Solution: SwitchResX app, change setting from `Billions of colors` to `Millions of colors`

## Guides & Useful Links

- [OpenCore Vanilla Desktop Guide](https://dortania.github.io/OpenCore-Install-Guide/)