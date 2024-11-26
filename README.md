# Hackintosh I5-7500 H270 GAMING M3 / Sequoia 15.2

<img src="https://github.com/Marcoun57/Hackintosh-I5-7500-H270-Sequoia-15.2/blob/main/i5-7500.jpg" width=30% height=30%>

<img src="https://github.com/Marcoun57/Hackintosh-I5-7500-H270-Sequoia-15.2/blob/main/h270-gaming-m3.png" width=50% height=50%>

Successfully installed macOS Sequoia 15.2 beta on PC with Opencore 1.0.2.

## Specs:

| Component  | Model |
| ------------- | ------------- |
| CPU  | Intel® Core™ i5-7500 Processor @ 3.80 GHz  |
| Architecture  | Kaby-Lake  |
| Graphics  | Intel® HD Graphics 630 / RX 570 4GB  |
| RAM  | 16GB DDR4 2400MHz 8GB x 2  |
| Storage  | Crucial 500GB SSD  |
| Audio  | Realtek ALC892 - layout 1  |
| Wifi / BT  | Fenvi T919  |


## Current status:

### Working:

- Audio
- Graphics with RX 570 (native)
- WiFi / Bluetooth Fenvi T919 (native) Airdrop, Handoff etc
- USB

## Bios setup:

### Disable

- Fast Boot
- Secure Boot
- Serial/COM Port
- Parallel Port
- VT-d
- CSM
- Thunderbolt
- Intel SGX
- Intel Platform Trust
- CFG Lock

### Enable

- VT-x
- Above 4G decoding
- Hyper-Threading
- Execute Disable Bit
- EHCI/XHCI Hand-off
- OS Type: Windows 8.1/10 UEFI Mode
- DVMT Pre-Allocated(iGPU Memory): 64MB
- SATA Mode: AHCI


## IMPORTANT

Please generate a new SMBIOS, I use MacPro 7.1, as I deleted my serials... with https://github.com/corpnewt/GenSMBIOS
