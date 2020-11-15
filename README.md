## ASUS ROG Strix B460-i

![information](https://w-md.imzsy.design/information.png)

## Hardware

- **Motherboard:** Asus ROG Strix B460-I
  - Ethernet: Intel® i219-V 1Gb Ethernet
  - Audio Codec: Realtek ALCS1220A (Layout 7)
  - Wireless: Intel® Wi-Fi 6 AX200
- **CPU:** Intel Core i7 10700
- **dGPU:** Sapphire RX 580 8GB
- **RAM:** Corsair Vengeance RGB PRO 16GB 2x8GB DDR4 3000Mhz
- **Storage:** Samsung SSD 970 EVO NVMe M.2（500GB）
  - Samsung SSD 860 EVO SATA III（500GB）
- **WiFi & Bluetooth:** BCM94352z(DW1560)

## Software

- **OS:** macOS Big Sur 11.0.1 
- **Bootloader:** OpenCore 0.6.3

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
-  Sapphire RX 580 (dGPU)
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