<div align="center">

# My Hardware Setup

My personal hardware setup.

</div>

<br><br>

## Desktop Computer

### Hardware

| Part                | Component                                                                                                                                                                                                                    | Link                                                                                                                                             |
| :------------------ | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------- |
| **Case**            | **Fractal Design Meshify 2 Compact**<br>ATX, Solid Black                                                                                                                                                                     | [Website](https://www.fractal-design.com/products/cases/meshify/meshify-2-compact/black-solid)                                                   |
| **Mainboard**       | **MSI MAG Z790 TOMAHAWK WIFI**<br>ATX, Intel Z790 Chipset, LGA 1700 Socket, DDR5 Memory (Intel XMP 3.0), PCIe 5.0 Expansion, PCIe 3.0 M.2, Intel 2.5Gbps LAN, Intel Wi-Fi 6E, Bluetooth 5.3                                  | [Website](https://de.msi.com/Motherboard/MAG-Z790-TOMAHAWK-WIFI)                                                                                 |
| **CPU**             | **Intel Core i7-13700K 3.4 GHz 16-Core**<br>16 Cores (24 threads) = 8 P-Cores (16 threads, 3.40GHz, 5.30GHz boost) + 8 E-Cores (8 threads, 2.50GHz, 4.20GHz boost), Intel UHD 770, LGA 1700 Socket, 125W / 253W Power Limits | [Website](https://www.intel.de/content/www/de/de/products/sku/230500/intel-core-i713700k-processor-30m-cache-up-to-5-40-ghz/specifications.html) |
| **RAM**             | **Kingston FURY Beast 64GB (2x 32GB) DDR5-6000 CL30**<br>64GB Dual Kit (2x 32GB), DDR5, 6000MT/s, CL30-36-36-80, 1.4V, Intel XMP 3.0, Black                                                                                  | [Website](https://www.kingston.com/de/memory/gaming/kingston-fury-beast-ddr5-memory)                                                             |
| **GPU**             | **ASUS ROG Strix GeForce RTX 4080 (OC Edition)**<br>2205MHz (2625MHz boost), 16GB GDDR6X VRAM (256bit, 22.4Gbps, 1400MHz)                                                                                                    | [Website](https://rog.asus.com/de/graphics-cards/graphics-cards/rog-strix/rog-strix-rtx4080-o16g-gaming-model)                                   |
| **PSU**             | **be quiet! DARK POWER 13**<br>Modular, 80 PLUS Titanium, 1000W, ATX 3.0 (incl. 12VHPWR for PCIe 5.0 GPUs)                                                                                                                   | [Website](https://www.bequiet.com/de/powersupply/4046)                                                                                           |
| **Storage**         | **Samsung 980 PRO 2TB NVMe M.2 SSD**                                                                                                                                                                                         | [Website](https://www.samsung.com/de/memory-storage/nvme-ssd/980-pro-2tb-nvme-pcie-gen-4-mz-v8p2t0bw/)                                           |
| **Storage**         | **2x Samsung 860 EVO 1TB SATA SSD**                                                                                                                                                                                          | [Website](https://www.samsung.com/de/memory-storage/860-evo-sata-3-2-5-inch-ssd/MZ-76E1T0BEU)                                                    |
| **CPU&nbsp;Cooler** | **Noctua NH-D15 chromax.black Dual-Tower**<br>+ Noctua NT-H2 thermal paste                                                                                                                                                   | [Website](https://noctua.at/en/nh-d15-chromax-black)                                                                                             |
| **Fans**            | **3x be quiet! Silent Wings 4 high-speed**<br>(PWM, 140mm, 1900 RPM)<br>**2x be quiet! Silent Wings 4 high-speed**<br>(PWM, 120mm, 2500 RPM)                                                                                 | [Website](https://www.bequiet.com/de/casefans/silent-wings-4/3696)                                                                               |

<br>

### BIOS / UEFI

| Name     | Version                    | Released     | Built        | Link                                                                          |
| :------- | :------------------------- | :----------- | :----------- | :---------------------------------------------------------------------------- |
| AMI BIOS | `7D91vHG` / `E7D91IMS.HG0` | `2025-04-22` | `2025-04-09` | [Website](https://de.msi.com/Motherboard/MAG-Z790-TOMAHAWK-WIFI/support#bios) |

#### Motherboard Settings

| Option                                                        | Value     |
| :------------------------------------------------------------ | :-------- |
| Advanced → PCIe/PCI Sub-system Settings → Re-Size BAR Support | `Enabled` |

#### Overclocking Settings

| Option                                                      | Value                                                       |
| :---------------------------------------------------------- | :---------------------------------------------------------- |
| OC Explore Mode                                             | `Expert`                                                    |
| Extreme Memory Profile (XMP)                                | `Enabled`<br>`(Profile 1: DDR5 6000MHz 30-36-36-80 1.400V)` |
| CPU Core Voltage Mode                                       | `Adaptive + Offset Mode`                                    |
| CPU Core Voltage Offset Mode                                | `-` _(minus)_                                               |
| CPU Core Voltage Offset                                     | `0.100`                                                     |
| CPU Cooler Tuning                                           | `Intel Default Settings`<br>`(PL1: 253W)`                   |
| Advanced CPU Configuration → Long Duration Power Limit (W)  | `150`                                                       |
| Advanced CPU Configuration → Short Duration Power Limit (W) | `150`                                                       |
| CPU Features → Intel Virtualization Tech                    | `Enabled`                                                   |

#### Fan Control (all)

| Option             | Value               |
| :----------------- | :------------------ |
| Mode               | `PWM`               |
| Temperature Source | `CPU`               |
| Step Up Time       | `0.1s`              |
| Step Down Time     | `0.1s`              |
| Smart Fan Mode     | Enabled _(checked)_ |

#### Fan Curve (all)

| Temperature | Fan Speed |
| :---------- | :-------- |
| 80°C        | 100%      |
| 70°C        | 70%       |
| 50°C        | 30%       |
| 0°C         | 30%       |

#### How to update / flash

Prepare:

1. Download and extract latest stable BIOS zip file (see above)
2. Move BIOS files onto a freshly formatted USB drive

Reset BIOS:

1. Boot into BIOS (repeatedly press `Delete` / `Entf` key during boot sequence)
2. Remember any custom BIOS settings and fan control configurations (see above)
3. Navigate to "Settings" → "Save & Exit"
4. Use "Restore Defaults" (and confirm)
5. Use "Save change and Reboot" (and confirm)

Update (flash) BIOS:

1. Boot into BIOS (repeatedly press `Delete` / `Entf` key during boot sequence)
2. Enter "M-Flash" mode (and confirm)
3. Select BIOS file from the USB drive (and confirm)
4. Wait until update is complete - don't touch anything!

Initial Check:

1. Let the system boot into Windows
2. Check if everything works normally (e.g. look at performance tab in task manager)

Re-apply custom BIOS settings:

1. Boot into BIOS (repeatedly press `Delete` / `Entf` key during boot sequence)
2. Re-apply any custom BIOS setting and fan control configurations (see above)

Full Check:

1. Let the system boot into Windows
2. Check if everything works normally (e.g. look at performance tab in task manager)
3. Run benchmarks, execute stress tests and test games as needed

<br>

### Firmware

| Name                                      | Version        | Released         | Link                                                                                                                          |
| :---------------------------------------- | :------------- | :--------------- | :---------------------------------------------------------------------------------------------------------------------------- |
| MSI Intel Management Engine (ME) Firmware | `16.1.35.2557` | `2025-03-13` (?) | [Website](https://de.msi.com/Motherboard/MAG-Z790-TOMAHAWK-WIFI/support#bios)                                                 |
| MSI USB Audio FW Update Tool              | ?              | `2024-05-13`     | [Website](https://de.msi.com/Motherboard/MAG-Z790-TOMAHAWK-WIFI/support#driver)                                               |
| MSI LED Firmware Tool                     | `v0007`        | `2023-01-10`     | [Website](https://de.msi.com/Motherboard/MAG-Z790-TOMAHAWK-WIFI/support#firmware)                                             |
| ASUS GPU VBIOS Update Tool                | `V1`           | `2023-03-02`     | [Website](https://rog.asus.com/de/graphics-cards/graphics-cards/rog-strix/rog-strix-rtx4080-o16g-gaming-model/helpdesk_bios/) |
| Samsung Magician                          | latest         | `2025-05-19` (?) | [Website](https://www.samsung.com/semiconductor/minisite/ssd/download/tools)                                                  |

<br><br>

## Peripherals & Devices

### Overview

| Type                | Product / Specs                                                                        | Link                                                                                                                |
| ------------------- | -------------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------------------------------- |
| **Monitor**         | **2x LG 27GL850-B**<br>(27'', 2560x1440px WQHD, IPS, 144Hz, HDR 10, G-Sync / FreeSync) | [Website](https://www.lg.com/de/monitore/lg-27GL850-B)                                                              |
| **Keyboard**        | **Logitech K280e Corded Keyboard**                                                     | [Website](https://www.logitech.com/de-de/product/corded-keyboard-k280e-business)                                    |
| **Mouse**           | **Logitech PRO X SUPERLIGHT 2** (black)                                                | [Website](https://www.logitechg.com/de-de/products/gaming-mice/pro-x2-superlight-wireless-mouse.910-006630.html)    |
| **Controller**      | **Microsoft Xbox Wireless Controller** (carbon black)                                  | [Website](https://www.xbox.com/de-DE/accessories/controllers/xbox-wireless-controller)                              |
| **Headset**         | **Logitech PRO X 2 LIGHTSPEED** (black)                                                | [Website](https://www.logitechg.com/de-de/products/gaming-audio/pro-x-2-wireless-headset.981-001263.html)           |
| **Speakers**        | **Bose Companion 20**                                                                  | [Website](https://www.bose.de/de_de/products/speakers/stereo_speakers/companion-20-multimedia-speaker-system.html)  |
| **Webcam**          | **Logitech Stream Cam** (graphite)                                                     | [Website](https://www.logitech.com/de-de/products/webcams/streamcam.960-001281.html)                                |
| **Microphone**      | **Audio Technica BP40**                                                                | [Website](https://www.audio-technica.com/de-de/bp40)                                                                |
| **Audio Interface** | **Focusrite Scarlett Solo (3rd Gen)**                                                  | [Website](https://focusrite.com/de/audio-interface/scarlett/scarlett-solo)                                          |
| **Microphone Arm**  | **RØDE PSA1+ Professional Studio Boom Arm**                                            | [Website](https://rode.com/de/accessories/stands-bars/psa1-plus)                                                    |
| **Router**          | **FRITZ!Box 6591 Cable Router**<br>(DOCSIS 3.1, Gigabit-LAN, WLAN AC + N)              | [Website](https://avm.de/produkte/fritzbox/fritzbox-6591-cable/)                                                    |
| **Printer**         | **HP OfficeJet Pro 8710**                                                              | [Website](https://support.hp.com/de-de/drivers/selfservice/hp-officejet-pro-8710-all-in-one-printer-series/7902014) |

<br>

### Mouse Settings

#### Windows

| Setting                   | Value                    |
| ------------------------- | ------------------------ |
| Mouse Pointer Speed       | `8` (5th tick in old UI) |
| Enhance Pointer Precision | `Off`                    |

#### Logitech G HUB

| Setting              | Value          |
| -------------------- | -------------- |
| Lightforce Switch    | `Optical Only` |
| Gaming Surface Mode  | `On`           |
| DPI                  | `800`          |
| Wireless Report Rate | `2000`         |

<br><br>

## Drivers & Tools

### Overview

| Name                                                                                                      | Description                                                  |
| --------------------------------------------------------------------------------------------------------- | ------------------------------------------------------------ |
| **[NVIDIA App](https://www.nvidia.com/de-de/software/nvidia-app/)**                                       | GPU driver and tool                                          |
| **[Logitech G HUB](https://www.logitechg.com/de-de/innovation/g-hub.html)**                               | Logitech peripherals tool (Mouse, Keyboard, Headset, Webcam) |
| **[Samsung Magician](https://www.samsung.com/semiconductor/minisite/ssd/download/tools)**                 | SSD (NVMe M.2, SATA) tool                                    |
| **[Xbox Accessories](https://apps.microsoft.com/detail/9nblggh30xj3)**                                    | XBOX Controller tool (e.g. Firmware Updates)                 |
| **[Voicemeter Potato](https://vb-audio.com/Voicemeeter/potato.htm)** (paid)                               | Audio mixer                                                  |
| **[Process Lasso](https://bitsum.com/)** (paid)                                                           | Process Manager                                              |
| **[Focusrite Control](https://downloads.focusrite.com/focusrite/scarlett-3rd-gen/scarlett-solo-3rd-gen)** | Audio Engine driver                                          |
| **[HP Smart](https://www.hpsmart.com/at/de)**                                                             | HP Printer tool                                              |
| **[Minimal ADB and Fastboot Tool](https://androidmtk.com/download-minimal-adb-and-fastboot-tool)**        | Connect to Android devices (Smartphone, TV)                  |

<br>

### NVIDIA App Settings

#### Drivers

| Option  | Value                                |
| ------- | ------------------------------------ |
| Drivers | `Game Ready Driver` (latest version) |

#### Display

| Option       | Value                  |
| ------------ | ---------------------- |
| Resolution   | `2560 x 1440 (native)` |
| Refresh Rate | `144 Hz`               |
| G-SYNC       | `On, Full screen`      |

#### Global Graphics

| Option                | Value                        |
| --------------------- | ---------------------------- |
| Monitor Technology    | `G-SYNC Compatible`          |
| Power Management Mode | `Prefer maximum performance` |
| Max Frame Rate        | `140 FPS`                    |
| Vertical Sync         | `On`                         |
| Low Latency Mode      | `Ultra`                      |
| Shader Cache Size     | `100 GB`                     |

#### How to clear / reset cache

Clearing caches (e.g. shader caches) can occasionally useful, i.e. after major driver updates or when encountering other issues.

Steps (in order, do not skip PC restarts):

1. Open the NVIDIA App and temporarily set "Shader Cache Size" to `Disabled`
2. *Restart PC*
3. Run "Disk Cleanup", check (at least) "DirectX Shader Cache" and confirm with "Ok"
4. Delete all file contents in `%AppData%\NVIDIA` and `%LocalAppData%\NVIDIA` (if applicable)
5. Delete any game-specific shader caches (e.g. `%AppData%\Arrowhead\Helldivers2\shader_cache`)
6. *Restart PC*
7. Open NVIDIA App, re-set "Shader Cache Size" back to `100 GB`
8. *Restart PC*

<br>

### Audio / Voicemeter Settings

All audio input and output channels are set to `48000Hz`.

Process-specific configuration (pinned via Process Lasso):

| Process              | CPU Priority | CPU Affinity |
| -------------------- | ------------ | ------------ |
| `audiodg.exe`        | High         | CPU 0        |
| `voicemeter8x64.exe` | High         | CPU 0        |

<br><br>

## Diagnostics & Monitoring & Benchmarking

### Overview

| Name                                                             | Description                                                     |
| ---------------------------------------------------------------- | --------------------------------------------------------------- |
| **[HWiNFO](https://www.hwinfo.com/)**                            | Hardware Diagnostics                                            |
| **[HWMonitor](https://www.cpuid.com/softwares/hwmonitor.html)**  | Hardware Monitoring                                             |
| **[MAXON CINEBENCH](https://www.maxon.net/de/cinebench)**        | Hardware Benchmarking / Stress Testing / Stability Verification |
| **[Heaven Benchmark 4.0](https://benchmark.unigine.com/heaven)** | Hardware Benchmarking / Stress Testing / Stability Verification |
