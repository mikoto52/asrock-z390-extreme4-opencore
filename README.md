# ASRock Z390 Extreme4 Hackintosh 

**Status: Inprogress | beta**

[![OpenCore](https://img.shields.io/badge/OpenCore-0.9.9-blue.svg)](https://github.com/acidanthera/OpenCorePkg) [![macOS-stable](https://img.shields.io/badge/macOS-14.4.1-brightgreen.svg)](https://www.apple.com/macos/sonoma-preview/)

<details>
<summary><strong>Hardware</strong></summary>
<br>

#### My system

| Category  | Component  | Note | 
| --------- | ---------- | ---- |
| CPU       | Intel(R) Core i5-8500 | |
| M/B       | [ASRock Z390 Extreme4]() | |
| GPU       | GIGABYTE Radeon RX 480 8GB | Need to BIOS Flash XFX.RX580.8192.190820.rom |
| NVMe      | SAMSUNG MZVLV512HCJH-00000 | Extra drive |
| NVMe      | MO2000KEFHR | Extra drive |
| SSD       | kimtigo SSD 120GB | Boot & OS Device |
| Ethernet  | Intel I219V7 PCI Express Gigabit Ethernet | |
| Monitor   | BenQ LCD | |

</details>

<details>
<summary><strong>Main software</strong></summary>
<br/>

| Component    | Version |
| ------------ | ------- |
| macOS Sonoma | 14.4.1  |
| OpenCore     | v0.9.8  |

</details>

<details>
<summary><strong>ACPI Files</strong></summary>
<br>


| Component                |
| ------------------------ |
| SSDT-HACK.aml            |
| SSDT-RHUB-Reset          |

</details>

## Status

<details>  
<summary><strong>What's working ✅</strong></summary>


- [x] GPU hardware acceleration / performance
- [x] iMessage, FaceTime, App Store, iTunes Store. `Generate your own SMBIOS`

</details>  

<details>  
<summary><strong>What's not working ⚠️</strong></summary>


- [ ] Testing in progress

</details>  

<details>  
<summary><strong>Untested 🧪</strong></summary>


- [ ] Boot chime - `should work I just haven't bothered`
- [ ] FileVault - `should work I just haven't tried it`

</details> 

<details>  
<summary><strong>Change log 🪵</strong></summary>


- **21 Apr 2024**
  - First release (RC)
</details>
