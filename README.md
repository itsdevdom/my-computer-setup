<div align="center">

# My Computer Setup

My computer setup, including peripherals and devices, firmware and drivers, software and configurations.

</div>

<br><br>

## Desktop Computer

### Hardware

#### Case

Fractal Design Meshify 2 Compact ([Website](https://www.fractal-design.com/products/cases/meshify/meshify-2-compact/black-solid))

| Spec        | Details |
| :---------- | :------ |
| Form Factor | ATX     |
| Panel       | Solid   |
| Color       | Black   |

#### Mainboard

MSI MAG Z790 TOMAHAWK WIFI ([Website](https://de.msi.com/Motherboard/MAG-Z790-TOMAHAWK-WIFI))

| Spec       | Details              |
| :--------- | :------------------- |
| Chipset    | Intel Z790           |
| CPU Socket | LGA 1700             |
| Memory     | DDR5 (Intel XMP 3.0) |
| Expansion  | PCIe 5.0             |
| M.2        | PCIe 3.0             |
| LAN        | Intel 2.5Gbps        |
| Wi-Fi      | Intel Wi-Fi 6E       |
| Bluetooth  | Intel Bluetooth 5.3        |

#### Processor (CPU)

Intel Core i7-13700K 3.4 GHz 16-Core ([Website](https://www.intel.de/content/www/de/de/products/sku/230500/intel-core-i713700k-processor-30m-cache-up-to-5-40-ghz/specifications.html))

| Spec         | Details                                        |
| :----------- | :--------------------------------------------- |
| Cores        | 16 Cores (24 threads)                          |
| P-Cores      | 8 P-Cores (16 threads, 3.40GHz, 5.30GHz boost) |
| E-Cores      | 8 E-Cores (8 threads, 2.50GHz, 4.20GHz boost)  |
| Socket       | LGA 1700                                       |
| Power Limits | 125W / 253W                                    |

#### Memory (RAM)

Kingston FURY Beast 64GB (2x 32GB) DDR5-6000 CL30 ([Website](https://www.kingston.com/de/memory/gaming/kingston-fury-beast-ddr5-memory))

| Spec         | Details        |
| :----------- | :------------- |
| Kit          | Dual Kit       |
| Capacity     | 64GB (2x 32GB) |
| Type         | DDR5           |
| Speed        | 6000MT/s       |
| Latency      | CL30-36-36-80  |
| Voltage      | 1.4V           |
| Profile (OC) | Intel XMP 3.0  |
| Color        | Black          |

#### Graphics Card (GPU)

ASUS ROG Strix GeForce RTX 4080 (OC Edition) ([Website](https://rog.asus.com/de/graphics-cards/graphics-cards/rog-strix/rog-strix-rtx4080-o16g-gaming-model))

| Spec        | Details                                 |
| :---------- | :-------------------------------------- |
| Clock Speed | 2205MHz (2625MHz boost)                 |
| VRAM        | 16GB GDDR6X (256bit, 22.4Gbps, 1400MHz) |
| Slot        | PCIe 4.0                                |

#### Power Supply (PSU)

be quiet! DARK POWER 13 1000W ([Website](https://www.bequiet.com/de/powersupply/4046))

| Spec       | Details                                   |
| :--------- | :---------------------------------------- |
| Type       | Modular                                   |
| Size       | ATX 3.0 (incl. 12VHPWR for PCIe 5.0 GPUs) |
| Efficiency | 80 PLUS Titanium                          |
| Power      | 1000W                                     |

#### Storage

Samsung 980 PR O 2TB NVMe M.2 SSD ([Website](https://www.samsung.com/de/memory-storage/nvme-ssd/980-pro-2tb-nvme-pcie-gen-4-mz-v8p2t0bw/))<br>
2x Samsung 860 EVO 1TB SATA SSD ([Website](https://www.samsung.com/de/memory-storage/860-evo-sata-3-2-5-inch-ssd/MZ-76E1T0BEU))

#### Cooling / Fans

Noctua NH-D15 chromax.black Dual-Tower ([Website](https://noctua.at/en/nh-d15-chromax-black))<br>
_with Noctua NT-H2 thermal paste ([Website](https://noctua.at/de/nt-h2-3-5g))_

3x be quiet! Silent Wings 4 high-speed ([Website](https://www.bequiet.com/de/casefans/silent-wings-4/3696))

| Spec               | Details |
| :----------------- | :------ |
| Connection / Power | PWM     |
| Dimension          | 140mm   |
| Max Speed          | 1900RPM |

2x be quiet! Silent Wings 4 high-speed ([Website](https://www.bequiet.com/de/casefans/silent-wings-4/3696))

| Spec               | Details |
| :----------------- | :------ |
| Connection / Power | PWM     |
| Dimension          | 120mm   |
| Max Speed          | 2500RPM |

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

| Option                                                      | Value                                                  |
| :---------------------------------------------------------- | :----------------------------------------------------- |
| OC Explore Mode                                             | `Expert`                                               |
| Extreme Memory Profile (XMP)                                | `Enabled (Profile 1: DDR5 6000MHz 30-36-36-80 1.400V)` |
| CPU Core Voltage Mode                                       | `Adaptive + Offset Mode`                               |
| CPU Core Voltage Offset Mode                                | `-` _(minus)_                                          |
| CPU Core Voltage Offset                                     | `0.100`                                                |
| CPU Cooler Tuning                                           | `Intel Default Settings (PL1: 253W)`                   |
| Advanced CPU Configuration → Long Duration Power Limit (W)  | `150`                                                  |
| Advanced CPU Configuration → Short Duration Power Limit (W) | `150`                                                  |
| CPU Features → Intel Virtualization Tech                    | `Enabled`                                              |

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

<br>

### Drivers

| Name                           | Version           | Released     | Link                                                                            |
| :----------------------------- | :---------------- | :----------- | :------------------------------------------------------------------------------ |
| Intel Chipset Driver           | `10.1.19899.8597` | `2025-01-13` | [Website](https://de.msi.com/Motherboard/MAG-Z790-TOMAHAWK-WIFI/support#driver) |
| Intel SVGA Drivers             | `32.0.101.5542`   | `2025-01-13` | [Website](https://de.msi.com/Motherboard/MAG-Z790-TOMAHAWK-WIFI/support#driver) |
| Intel Management Engine Driver | `2435.6.36.0`     | `2025-03-17` | [Website](https://de.msi.com/Motherboard/MAG-Z790-TOMAHAWK-WIFI/support#driver) |
| Intel GNA Scoring Accelerator  | `3.05.00.1578`    | `2025-01-13` | [Website](https://de.msi.com/Motherboard/MAG-Z790-TOMAHAWK-WIFI/support#driver) |
| Intel Serial IO Drivers        | `30.100.2417.30`  | `2025-01-13` | [Website](https://de.msi.com/Motherboard/MAG-Z790-TOMAHAWK-WIFI/support#driver) |
| Intel Network Drivers          | `2.1.5.3`         | `2025-03-18` | [Website](https://de.msi.com/Motherboard/MAG-Z790-TOMAHAWK-WIFI/support#driver) |
| Intel WIFI Driver              | `23.40.0.4`       | `2024-04-30` | [Website](https://de.msi.com/Motherboard/MAG-Z790-TOMAHAWK-WIFI/support#driver) |
| BlueTooth Driver               | `23.40.0.2`       | `2024-04-15` | [Website](https://de.msi.com/Motherboard/MAG-Z790-TOMAHAWK-WIFI/support#driver) |
| Realtek HD Universal Driver    | `6.4.0.2413`      | `2025-04-07` | [Website](https://de.msi.com/Motherboard/MAG-Z790-TOMAHAWK-WIFI/support#driver) |

<br>

### Disabled Devices (via Windows Device Manager)

| Category         | Device                          | Reason                                                                      |
| ---------------- | ------------------------------- | --------------------------------------------------------------------------- |
| Network Adapters | Intel(R) Wi-Fi 6E AX211 160Mhz  | Unused<br>→ Intel (R) Ethernet Controller I226-V is used instead            |
| Bluetooth        | Intel(R) Wireless Bluetooth (R) | Unused & Conflicting<br>→ TP-Link Bluetooth 5.4 USB Adapter is used instead |

<br>

### NVIDIA App

| Name       | Version | Link                                                        |
| :--------- | :------ | :---------------------------------------------------------- |
| NVIDIA App | latest  | [Website](https://www.nvidia.com/de-de/software/nvidia-app) |

#### Drivers

| Option | Value                       |
| :----- | :-------------------------- |
| Driver | `GeForce Game Ready Driver` |

#### System → Display

| Option       | Value                  |
| :----------- | :--------------------- |
| G-SYNC       | `On, Full screen`      |
| Resolution   | `2560 x 1440 (native)` |
| Refresh Rate | `144 Hz`               |

#### Graphics → Global Settings

| Option                | Value                        |
| :-------------------- | :--------------------------- |
| Power Management Mode | `Prefer maximum performance` |
| Monitor Technology    | `G-SYNC Compatible`          |
| Vertical Sync         | `On`                         |
| Max Frame Rate        | `140 FPS`                    |
| Low Latency Mode      | `Ultra`                      |
| Shader Cache Size     | `100 GB`                     |

#### How to clear / reset shader cache

Temporarily disable shader cache:

1. In the NVIDIA App, navigate to "Graphics" → "Global Settings" and set "Shader Cache Size" to `Disabled`
2. Restart PC

Delete shader caches:

1. Run the Windows "Disk Cleanup" as Administrator, check at least "DirectX Shader Cache" (consider "Temporary Files" as well) and confirm with "Ok"
2. Cleanup NVIDIA shader caches in `%AppData%\NVIDIA`, `%LocalAppData%\NVIDIA` and `%LocalAppData%\D3DSCache`
3. Cleanup any game-specific shader caches (e.g. for Helldivers 2 in `%AppData%\Arrowhead\Helldivers2\shader_cache`)
4. Restart PC

Re-enable shader cache:

1. In the NVIDIA App, navigate to "Graphics" → "Global Settings" and set "Shader Cache Size" back to `100 GB`
2. Restart PC

<br><br>

## Peripherals

### USB Hub

#### Hardware

LIONWEI USB Hub ([Website](https://www.amazon.de/dp/B0BRXQ5LG8))

<br>

### Bluetooth

#### Hardware

TP-Link UB500 ([Website](https://www.tp-link.com/de/home-networking/adapter/ub500/))

<br>

### Monitor

#### Hardware

LG 27GL850-B ([Website](https://www.lg.com/de/monitore/lg-27GL850-B))

<br>

### Keyboard

#### Hardware

Keychron V6 Max ([Website](https://keychron.de/de/products/keychron-v6-max-qmk-wireless-custom-mechanical-keyboard-iso-layout-collection?variant=42587534491785))

| Spec         | Details                    |
| :----------- | :------------------------- |
| Size         | Full Size (100%)           |
| Layout       | DE-ISO                     |
| Switches     | Gateron Jupiter Brown      |
| Connectivity | Cable / 2.4GHz / Bluetooth |

#### Hardware Settings

| Option       | Value                                                            |
| :----------- | :--------------------------------------------------------------- |
| System       | `Windows`                                                        |
| Connectivity | `2.4G` during normal use<br>`Cable` while charging / to turn off |

#### Firmware / Driver / Software

Keychron Launcher ([Web Application](https://launcher.keychron.com)), incl. QMK Toolbox for Firmware updates

#### Windows Settings

| Option                                            | Value |
| :------------------------------------------------ | :---- |
| Accessibility → Keyboard → Sticky Keys → Shortcut | `Off` |

#### Keychron Launcher

With "Layout language" set to "Deutsch", following keymap customizations are applied:

| Default Key                      | Mapped Key               | Physical Keycap |
| :------------------------------- | :----------------------- | :-------------- |
| "Rollen" (above "Home")          | Lighting → RGB Toggle    | Lightbulb       |
| "Pause / Umbr" (above "Page Up") | Custom → Any → `G(KC_L)` | Lock            |

<br>

### Mouse

#### Hardware

Logitech PRO X SUPERLIGHT 2 ([Website](https://www.logitechg.com/de-de/products/gaming-mice/pro-x2-superlight-wireless-mouse.910-006630.html))

| Spec                    | Details               |
| :---------------------- | :-------------------- |
| Tracking                | HERO 2                |
| Resolution              | 100DPI - 44000DPI     |
| Polling Rate (Wireless) | up to 8000Hz          |
| Polling Rate (Wired)    | up to 1000Hz          |
| Connection              | Wireless (LIGHTSPEED) |
| Color                   | Black                 |

#### Firmware / Driver / Software

Logitech G HUB ([Website](https://www.logitechg.com/de-de/innovation/g-hub.html))

#### Windows Settings

| Option                                                    | Value               |
| :-------------------------------------------------------- | :------------------ |
| Bluetooth and Devices → Mouse → Mouse Pointer Speed       | `8` (`5` in old UI) |
| Bluetooth and Devices → Mouse → Enhance Pointer Precision | `Off`               |

#### Logitech G HUB

| Option                                | Value          |
| :------------------------------------ | :------------- |
| Device Settings → Lightforce Switch   | `Optical Only` |
| Device Settings → Gaming Surface Mode | `On`           |
| Sensitivity → Default DPI             | `800 DPI`      |
| Sensitivity → Wireless Report Rate    | `2000`         |

<br>

### Controller

#### Hardware

Microsoft Xbox Wireless Controller ([Website](https://www.xbox.com/de-DE/accessories/controllers/xbox-wireless-controller))

#### Firmware / Driver / Software

Xbox Accessories ([Microsoft Store](https://apps.microsoft.com/detail/9NBLGGH30XJ3))

In Steam: Install "Xbox Extended Feature Support Driver"

<br>

### Speakers

#### Hardware

Bose Companion 20 ([Website](https://www.bose.de/de_de/products/speakers/stereo_speakers/companion-20-multimedia-speaker-system.html))

<br>

### Headset

#### Hardware

Logitech PRO X 2 LIGHTSPEED ([Website](https://www.logitechg.com/de-de/products/gaming-audio/pro-x-2-wireless-headset.981-001263.html))

| Spec               | Details                                  |
| :----------------- | :--------------------------------------- |
| Driver             | Graphene 1.97in (50mm)                   |
| Magnet             | Neodymium                                |
| Frequency Response | 20Hz - 20KHz                             |
| Impedance          | 38Ohms                                   |
| Sensitivity        | 87.8dB SPL @ 1mW & 1cm                   |
| Connection         | Wireless (2.4GHz LIGHTSPEED) / Bluetooth |
| Color              | Black                                    |

#### Firmware / Driver / Software

Logitech G HUB ([Website](https://www.logitechg.com/de-de/innovation/g-hub.html))

<br>

### Microphone

#### Hardware

Audio Technica BP40 ([Website](https://www.audio-technica.com/de-de/bp40))<br>
on RØDE PSA1+ Professional Studio Boom Arm ([Website](https://rode.com/de/accessories/stands-bars/psa1-plus))

| Spec                     | Details                    |
| :----------------------- | :------------------------- |
| Element                  | Dynamic                    |
| Polar Pattern            | Hypercardioid              |
| Frequency Response       | 50Hz - 16000Hz             |
| Low Frequency Roll Off   | 100Hz, 6dB/octave          |
| Open Circuit Sensitivity | -48dB (3.9mV) re 1V at 1Pa |
| Connector                | Integral 3-pin XLRM-type   |

Focusrite Scarlett Solo (3rd Gen) ([Website](https://focusrite.com/de/audio-interface/scarlett/scarlett-solo))

<br>

### Webcam

#### Hardware

Insta360 Link 2C ([Website](https://www.insta360.com/de/product/insta360-link2))

| Spec          | Details                                                                                         |
| :------------ | :---------------------------------------------------------------------------------------------- |
| Resolution    | 4K @ 30/25/24fps<br>720p @ 60/50/30/25/24fps<br>1080p @ 60/50/30/25/24fps<br>360p @ 30/25/24fps |
| Encoding      | H.264<br>MJPEG                                                                                  |
| ISO           | 100 - 3200                                                                                      |
| Shutter Speed | 1/8000 - 1/30s                                                                                  |
| White Balance | 2000 - 10000K                                                                                   |
| Aperture      | F1.8                                                                                            |
| FOV           | 79.5º DFOV / 67º HFOV                                                                           |
| Connector     | USB-C                                                                                           |
| Color         | Graphite Black                                                                                  |

#### Firmware / Driver / Software

Insta360 Link Controller ([Website](https://www.insta360.com/de/download/insta360-link2c))

<br>

### Voicemeter

#### Driver / Software

Voicemeter Potato (64-Bit Version) ([Website](https://vb-audio.com/Voicemeeter/potato.htm))

#### Windows Settings

| Option                                         | Value                                                                                        |
| :--------------------------------------------- | :------------------------------------------------------------------------------------------- |
| System → Sound → [Device] → Channels           | `2` (or `1` if not available)                                                                |
| System → Sound → [Device] → Bitrate            | `16bit`                                                                                      |
| System → Sound → [Device] → Sample Rate        | `48000Hz`                                                                                    |
| System → Sound → [Device] → Volume             | `100` (baseline, can of course be changed later on)                                          |
| System → Sound → [Device] → Audio Enhancements | `Device Default Effects` only if powered by Realtek or Logitech<br>`Off` for everything else |
| System → Sound → [Device] → Spatial Sound      | `Off`                                                                                        |
| System → Sound → [Device] → Voice Focus        | `Off`                                                                                        |

#### Virtual Cables

| Input (Hardware / Virtual)                   | Voicemeter Input | Voicemeter Output  | Output (Hardware / Virtual)                          |
| :------------------------------------------- | :--------------- | :----------------- | :--------------------------------------------------- |
| Windows Default Output Device                | Voicemeter Input | Hardware Output A1 | _Hardware Output Device<br>(e.g. speakers, headset)_ |
| _Hardware Input Device<br>(e.g. microphone)_ | Stereo Input 1   | Voicemeter Out B1  | Windows Default Input Device                         |

#### Hardware Input & Output

| Option       | Value                                                                                             |
| :----------- | :------------------------------------------------------------------------------------------------ |
| Audio Driver | Preferably `WDM (WADAPI)`<br>Alternatively `MME (Multimedia)` if audio crackling / popping occurs |

#### System Settings

| Option                    | Value     |
| :------------------------ | :-------- |
| Preferred Main SampleRate | `48000Hz` |

#### Hardware Input Processing

| Option            | Value                                                                               |
| :---------------- | :---------------------------------------------------------------------------------- |
| Voice Color Panel | bottom left square,<br>with distance of 1x handle size between handle and each axis |
| Compressor        | `0.5`                                                                               |
| Gate              | `0.1`                                                                               |
| Denoiser          | `1.0`                                                                               |
| Limit             | `-0.3`                                                                              |

#### Process Optimization (via Process Lasso)

| Process Name         | CPU Priority | CPU Affinity |
| -------------------- | ------------ | ------------ |
| `audiodg.exe`        | `High`       | `CPU 0`      |
| `voicemeter8x64.exe` | `High`       | `CPU 0`      |

<br><br>

## Other Devices

### Router

#### Hardware

FRITZ!Box 6591 Cable ([Website](https://avm.de/produkte/fritzbox/fritzbox-6591-cable))

| Spec                 | Details                                                       |
| :------------------- | :------------------------------------------------------------ |
| Data Transfer        | Cable (DOCSIS 3.1)                                            |
| Max Speed Downstream | 6000Mbit                                                      |
| Max Speed Upstream   | 2000Mbit                                                      |
| LAN                  | 1 Gigabit/s                                                   |
| WLAN                 | WiFi 5 / 802.11ac (1.733MBit/s @ 5GHz / 800 MBit/s @ 2,4 GHz) |

#### Firmware

FRITZ!OS ([FRITZ!Box](http://fritz.box/), [MyFritz!Net](https://www.myfritz.net/))

#### Settings

| Option                                                                         | Value                                                   |
| :----------------------------------------------------------------------------- | :------------------------------------------------------ |
| Internet → Zugangsdaten → DNSv4-Server → Bevorzugter DNS-Server                | `1.1.1.1`                                               |
| Internet → Zugangsdaten → DNSv4-Server → Alternativer DNS-Server               | `1.0.0.1`                                               |
| Internet → Zugangsdaten → DNSv6-Server → Bevorzugter DNS-Server                | `2606:4700:4700::1111`                                  |
| Internet → Zugangsdaten → DNSv6-Server → Alternativer DNS-Server               | `2606:4700:4700::1001`                                  |
| Internet → Zugangsdaten → Bei Störung auf öffentliche DNS-Server zurückgreifen | Aktiviert                                               |
| Internet → Zugangsdaten → DNS over TLS (DoT)                                   | Aktiviert                                               |
| Internet → Zugangsdaten → DNS over TLS (DoT) → Zertifikatsprüfung erzwingen    | Aktiviert                                               |
| Internet → Zugangsdaten → DNS over TLS (DoT) → Fallback zulassen               | Aktiviert                                               |
| Internet → Zugangsdaten → DNS over TLS (DoT) → Auslösungsnamen der DNS-Server  | `one.one.one.one`<br>`1dot1dot1dot1.cloudflare-dns.com` |

<br>

### Printer

#### Hardware

HP OfficeJet Pro 8710 ([Website](https://support.hp.com/de-de/drivers/selfservice/hp-officejet-pro-8710-all-in-one-printer-series/7902014))

#### Software

HP Smart ([Microsoft Store](https://apps.microsoft.com/detail/9WZDNCRFHWLH))

<br><br>

## Tools

| Name                                                                                               | Description                                                     |
| -------------------------------------------------------------------------------------------------- | --------------------------------------------------------------- |
| **[Process Lasso](https://bitsum.com)**                                                            | Process Manager                                                 |
| **[Minimal ADB and Fastboot Tool](https://androidmtk.com/download-minimal-adb-and-fastboot-tool)** | Connect to Android devices (Smartphone, TV)                     |
| **[HWiNFO](https://www.hwinfo.com/)**                                                              | Hardware Diagnostics                                            |
| **[MAXON CINEBENCH](https://www.maxon.net/de/cinebench)**                                          | Hardware Benchmarking / Stress Testing / Stability Verification |
| **[Heaven Benchmark 4.0](https://benchmark.unigine.com/heaven)**                                   | Hardware Benchmarking / Stress Testing / Stability Verification |
