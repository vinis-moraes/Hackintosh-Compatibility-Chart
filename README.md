 This repository contains informations about hardware compatibility with hackintosh

## Table of contents
>- [CPU Compatibility](#cpu-compatibility)
>   - [Intel Desktop](#intel-desktop)
>   - [Intel Laptop](#intel-laptop)
>   - [Intel HEDT](#intel-hedt-high-end-desktop)
>   - [AMD Desktop](#amd-desktop)
>   - [AMD Laptop](#amd-laptop)
>- [Graphics Compatibility](#graphics-compatibility)
>   - [NVIDIA Support](#nvidia-support)
>   - [AMD/ATI Support](#amdati-support)
>   - [Intel Support](#intel-support)
>- [Storage Compatibility](#storage-compatibility)
>- [Wired Network](#wired-network)
>- [Wireless Network](#wireless-network)
>- [Other](#fingerprint-sensors)



## [🔝](#table-of-contents)CPU Compatibility
### [🔝](#table-of-contents)Intel Desktop

CPU Generation/macOS Version | Tiger (10.4) | Leopard (10.5) | Snow Leopard (10.6) | Lion (10.7) | Mountain Lion (10.8) | Mavericks (10.9) | Yosemite (10.10) | El Capitain (10.11) | Sierra (10.12) | High Sierra (10.13) | Mojave (10.14) | Catalina (10.15) | Big Sur (11) | Monterrey (12) | Ventura (13) | Sonoma (14) | Sequoia (15)
---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---
**Yonah, Conroe and Penryn(Core and Core 2)** | ✅¹ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️² | ⚠️³ | ⚠️³ | ⚠️³ | ⚠️³| ⚠️³ | ⚠️³ | ⚠️³   
**Lynnfield and Clarkdale(1st)** | 🚫 | 🚫 | ✅⁴ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️³ | ⚠️³ | ⚠️³
**Sandy Bridge(2nd)** | 🚫 | 🚫 | ✅⁵ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️³ | ⚠️³ | ⚠️³
**Ivy Bridge(3rd)** | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️³ | ⚠️³ | ⚠️³
**Haswell(4th and 5th)** | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅
**Skylake(6th)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅
**Kaby Lake(7th)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅
**Coffee Lake(8th and 9th)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅
**Comet Lake (10th)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅

>¹ Starts at Mac OS X Tiger 10.4.10

>² As Yonah and Conroe CPUs don't support SSE4, they can only boot up to Sierra. Penryn does support SSE4, so it works natively with High Sierra

>³ Old CPUs support for newer versions of macOS may require OpenCore Legacy Patcher or CryptexFixup kext (CPUs that don't support AVX2)

>⁴ Starts at OS X Snow Leopard 10.6.3

>⁵ Starts at OS X Snow Leopard 10.6.7

### [🔝](#table-of-contents)Intel Laptop

CPU Generation/macOS Version | Tiger (10.4) | Leopard (10.5) | Snow Leopard (10.6) | Lion (10.7) | Mountain Lion (10.8) | Mavericks (10.9) | Yosemite (10.10) | El Capitain (10.11) | Sierra (10.12) | High Sierra (10.13) | Mojave (10.14) | Catalina (10.15) | Big Sur (11) | Monterrey (12) | Ventura (13) | Sonoma (14) | Sequoia (15)
---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---
**Clarksfield and Arrandale (1st)** | 🚫 | 🚫 | ✅⁴ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️³ | ⚠️³ | ⚠️³ | ⚠️³ | ⚠️³ | ⚠️³ | ⚠️³
**Sandy Bridge(2nd)** | 🚫 | 🚫 | ✅⁵ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️³ | ⚠️³ | ⚠️³ | ⚠️³ | ⚠️³ | ⚠️³ | ⚠️³
**Ivy Bridge(3rd)** | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️³ | ⚠️³ | ⚠️³ | ⚠️³
**Haswell(4th)** | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️⁶ | ⚠️⁶ | ⚠️⁶
**Broadwell(5th)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️⁶ | ⚠️⁶ | ⚠️⁶
**Sky Lake(6th)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️⁶ | ⚠️⁶ | ⚠️⁶
**Kaby Lake and Amber Lake Y (7th)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ 
**Coffee Lake(8th)**  | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ 
**Whiskey Lake(8th)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅⁷ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ 
**Coffee Lake Plus(9th)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ 
**Comet Lake(10th)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ 
**Ice Lake(10th)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ 


> _Due to the fact that most laptops rely only on Integrated Graphics, check GPU Compatibility. Most iGPUs can be used with OpenCore Legacy Patcher to provide support for newer OS releases_

>³ Old CPUs support for newer versions of macOS may require OpenCore Legacy Patcher or CryptexFixup kext (CPUs that don't support AVX2)

>⁶ CPU is supported, but iGPU is not. Use OpenCore Legacy Patcher to have Graphics Acceleration

>⁷ Starts at macOS 10.14.1

### [🔝](#table-of-contents)Intel HEDT (High End Desktop)

CPU Generation/macOS Version | Tiger (10.4) | Leopard (10.5) | Snow Leopard (10.6) | Lion (10.7) | Mountain Lion (10.8) | Mavericks (10.9) | Yosemite (10.10) | El Capitain (10.11) | Sierra (10.12) | High Sierra (10.13) | Mojave (10.14) | Catalina (10.15) | Big Sur (11) | Monterrey (12) | Ventura (13) | Sonoma (14) | Sequoia (15)
---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---
**Nehalem and Westmere** | 🚫 | ✅⁸ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️³ | ⚠️³ | ⚠️³
**Sandy and Ivy Bridge-E** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️³ | ⚠️³ | ⚠️³
**Haswell-E** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅
**Broadwell-E**  | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅
**Skylake-X/W and Cascade Lake-X/W** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ 

### [🔝](#table-of-contents)AMD Desktop

CPU Generation/macOS Version | Tiger (10.4) | Leopard (10.5) | Snow Leopard (10.6) | Lion (10.7) | Mountain Lion (10.8) | Mavericks (10.9) | Yosemite (10.10) | El Capitain (10.11) | Sierra (10.12) | High Sierra (10.13) | Mojave (10.14) | Catalina (10.15) | Big Sur (11) | Monterrey (12) | Ventura (13) | Sonoma (14) | Sequoia (15)
---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---
**Bulldozer and Jaguar** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️³ | ⚠️³ | ⚠️³
**Ryzen and Threadripper** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅

>³ Old CPUs support for newer versions of macOS may require OpenCore Legacy Patcher or CryptexFixup kext (CPUs that don't support AVX2)

### [🔝](#table-of-contents)AMD Laptop

CPU Generation/macOS Version | Tiger (10.4) | Leopard (10.5) | Snow Leopard (10.6) | Lion (10.7) | Mountain Lion (10.8) | Mavericks (10.9) | Yosemite (10.10) | El Capitain (10.11) | Sierra (10.12) | High Sierra (10.13) | Mojave (10.14) | Catalina (10.15) | Big Sur (11) | Monterrey (12) | Ventura (13) | Sonoma (14) | Sequoia (15)
---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---
**Ryzen** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅

>The OpenCore Team does not provide guides to build Ryzentoshes on laptops. On the other side, there are reports of various succesful builds using laptops with Ryzen and Integrated Graphics over the Internet

## [🔝](#table-of-contents)Graphics Compatibility

### [🔝](#table-of-contents)NVIDIA Support

Apple dropped support for NVIDIA GPUs in High Sierra, so only GPUs compatible at this time work on macOS

GPU Family/macOS Version | Tiger (10.4) | Leopard (10.5) | Snow Leopard (10.6) | Lion (10.7) | Mountain Lion (10.8) | Mavericks (10.9) | Yosemite (10.10) | El Capitain (10.11) | Sierra (10.12) | High Sierra (10.13) | Mojave (10.14) | Catalina (10.15) | Big Sur (11) | Monterrey (12) | Ventura (13) | Sonoma (14) | Sequoia (15)
---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---
**GeForce 6(6xxx)** | ✅ | ✅ | ✅ | ✅ | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫
**GeForce 7(7xxx)** | ✅ | ✅ | ✅ | ✅ | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫
**GeForce 8(8xxx)** | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸
**GeForce 9(9xxx)** | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸
**Tesla (1xx, 2xx, 3xx  )** | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸
**Fermi (4xx, 5xx)** | 🚫 | 🚫 | 🚫  | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸
**Fermi Rebranded (GTX 6xx, 7xx)** | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸
**Kepler(GTX 6xx, 7xx)** | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸
**Maxwell(GTX 745, 750/Ti, 9xx)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸
**Pascal(GTX 10xx)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸ | ⚠️⁸

>⁸ Modern macOS doesn't support natively NVIDIA GPUs. Use OpenCore Legacy Patcher to add support to these chips (you may find some issues with these hardwares)

Newer generations, like GTX 16xx, RTX 20xx, RTX 30xx, RTX 40xx or RTX 50xx have no support on macOS.

### [🔝](#table-of-contents)AMD/ATI Support

GPU Family/macOS Version | Tiger (10.4) | Leopard (10.5) | Snow Leopard (10.6) | Lion (10.7) | Mountain Lion (10.8) | Mavericks (10.9) | Yosemite (10.10) | El Capitain (10.11) | Sierra (10.12) | High Sierra (10.13) | Mojave (10.14) | Catalina (10.15) | Big Sur (11) | Monterrey (12) | Ventura (13) | Sonoma (14) | Sequoia (15)
---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---
**ATI X800(8xx)** | ✅ | ✅ | ✅ | ✅ | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫
**ATI X1000(1xxx)** | ✅ | ✅ | ✅ | ✅ | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫
**ATI HD 2000(2xxx)** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️⁹ | ⚠️⁹ | ⚠️⁹ | ⚠️⁹ | ⚠️⁹ | ⚠️⁹ | ⚠️⁹
**ATI HD 3000(3xxx)** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️⁹ | ⚠️⁹ | ⚠️⁹ | ⚠️⁹ | ⚠️⁹ | ⚠️⁹ | ⚠️⁹
**ATI HD 4000(4xxx)** | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️⁹ | ⚠️⁹ | ⚠️⁹ | ⚠️⁹ | ⚠️⁹ | ⚠️⁹ | ⚠️⁹
**HD 5000(5xxx)** | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️⁹ | ⚠️⁹ | ⚠️⁹ | ⚠️⁹ | ⚠️⁹ | ⚠️⁹ | ⚠️⁹
**HD 6000(6xxx)** | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️⁹ | ⚠️⁹ | ⚠️⁹ | ⚠️⁹ | ⚠️⁹ | ⚠️⁹ | ⚠️⁹
**HD 7000(7xxx)** | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️⁹ | ⚠️⁹ | ⚠️⁹
**HD 8000(8xxx)** | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️⁹ | ⚠️⁹ | ⚠️⁹
**R7/R9** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️⁹ | ⚠️⁹ | ⚠️⁹
**Polaris(RX 4xx, 5xx)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅¹⁰ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅
**Vega 10** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅
**Vega 20(Radeon VII)** | 🚫 | 🚫  | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅¹¹ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅
**Navi 10(RX 5xxx)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅¹²| ✅ | ✅ | ✅ | ✅ | ✅
**Navi 21(RX 69xx, 68xx)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅¹³ | ✅ | ✅ | ✅ | ✅
**Navi 23(RX 66xx)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅¹⁴ | ✅ | ✅ | ✅

>⁹ Legacy AMD/ATI GPUs need OpenCore Legacy Patcher to work on newer versions of macOS

>¹⁰ Starts at 10.12.6

>¹¹ Starts at 10.14.5

>¹² Starts at 10.15.1

>¹³ Starts at 11.4

>¹⁴ Starts at 12.1

Navi 24 (RX 6300, 6400, 6500XT) is not compatible **yet**. The project called [NootRX](https://chefkissinc.github.io/applehax/nootrx/) aims to bring support to these GPUs

iGPU Compatibility depends on [NootedRed kext](https://chefkissinc.github.io/applehax/nootedred/). Use this if your hacking a laptop with Ryzen and Vega or RDNA Graphics

### [🔝](#table-of-contents)Intel Support

GPU Family/macOS Version | Tiger (10.4) | Leopard (10.5) | Snow Leopard (10.6) | Lion (10.7) | Mountain Lion (10.8) | Mavericks (10.9) | Yosemite (10.10) | El Capitain (10.11) | Sierra (10.12) | High Sierra (10.13) | Mojave (10.14) | Catalina (10.15) | Big Sur (11) | Monterrey (12) | Ventura (13) | Sonoma (14) | Sequoia (15)
---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---
**3rd Gen GMA** | ✅ | ✅ | ✅ | ✅ | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫
**4th Gen GMA(3000, 3500, 4500)** | 🚫 | ✅ | ✅ | ✅ | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫
**HD Graphics(1st Gen, Westmere)** | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️¹⁵ | ⚠️¹⁵ | ⚠️¹⁵ | ⚠️¹⁵ | ⚠️¹⁵ | ⚠️¹⁵ | ⚠️¹⁵
**HD Graphics 2000¹⁶, 3000 (Sandy Bridge)** | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️¹⁵ | ⚠️¹⁵ | ⚠️¹⁵ | ⚠️¹⁵ | ⚠️¹⁵ | ⚠️¹⁵ | ⚠️¹⁵
**HD Graphics 2500¹⁶, 4000 (Ivy Bridge)** | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️¹⁵ | ⚠️¹⁵ | ⚠️¹⁵ | ⚠️¹⁵
**HD Graphics 4200-5100 (Haswell)** | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️¹⁵ | ⚠️¹⁵ | ⚠️¹⁵ 
**HD Graphics 5300-6200, Iris P6300 (Broadwell)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅¹⁷ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️¹⁵ | ⚠️¹⁵ | ⚠️¹⁵ 
**HD 515-530, Iris 540-580 (Skylake)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅¹⁸ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️¹⁹| ⚠️¹⁹ | ⚠️¹⁹
**HD 615-630, Iris Plus 640, 650 (Kaby Lake)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅²⁰ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅
**UHD 615-630, Iris Plus 645, 655 (8th, 9th, 10th)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅²¹ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅
**Iris Plus G4, G7 (Ice Lake)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫  | 🚫 | ✅²² | ✅ | ✅ | ✅ | ✅ | ✅

>¹⁵ Legacy Intel iGPU need OpenCore Legacy Patcher on newer versions of macOS

>¹⁶ 2xxx series can only be used for Quicksync

>¹⁷ Starts at 10.10.2

>¹⁸ Starts at 10.11.4

>¹⁹ macOS Ventura drops support for Skylake iGPUs. However, since Skylake and Kaby Lake iGPUs are so similar, Skylake iGPUs can be spoofed as Kaby Lake in order to make use of the Kaby Lake kexts, which are still present in Ventura and Sonoma. [Check here for more information](https://dortania.github.io/GPU-Buyers-Guide/modern-gpus/intel-gpu.html#skylake-6xxx)

>²⁰ Starts at 10.12.6

>²¹ Starts at 10.13.6

>²² Starts at 10.15.4

Newer iGPU (based on Xe), dGPU (based on Xe) and GT1 are **not** compatible **and will never be**.

## [🔝](#table-of-contents)Storage Compatibility

99.99% of the HDD and SSD models are compatible with macOS. There are only a few exceptions:

- Samsung PM981, PM991 and Micron 2200S NVMe SSDs: use NVMeFix kext to solve kernel panic problems;
- Optane: doesn't work at all, disable in BIOS an/or remove the drive.

## [🔝](#table-of-contents)Wired Network

99.99% of wired network solutions should work in one way or another, so probably you won't have problems with that.

## [🔝](#table-of-contents)Wireless Network

Well... here the problem comes. Most of Wi-FI cards that come with laptops are not supported by default, but there are kexts to fix most of them

* Intel Wireless - work on newer versions of macOS with [OpenIntelWireless solutions](https://openintelwireless.github.io/); Bluetooth support with [this kext](https://github.com/OpenIntelWireless/IntelBluetoothFirmware/releases).
* Atheros - since Mojave, Apple dropped the native support for these chipsets. Use [this](https://github.com/khronokernel/IO80211-Patches/blob/main/10.13.6-High-Sierra-Kexts/IO80211HighSierra.kext.zip) to have Wi-Fi and [this](https://github.com/zxystd/AthBluetoothFirmware/releases) to Bluetooth.
* Broadcom - for non-Apple adapters, use [this](https://github.com/acidanthera/AirportBrcmFixup) and [this](https://github.com/acidanthera/BrcmPatchRAM/releases) to have support. Read more about it at [OpenCore Documentation](https://dortania.github.io/Wireless-Buyers-Guide/Kext.html#broadcom).

## [🔝](#table-of-contents)Fingerprint Sensors

No support at all.

## [🔝](#table-of-contents)Face Recognition

Maybe you'll get your camera working, nothing else.

## [🔝](#table-of-contents)Intel Smart Sount Technology

Won't work, as Macs don't even know what this is.

## [🔝](#table-of-contents)Headphone Jack Combo

There are chances of working, as well as not. Test and see the results.

## [🔝](#table-of-contents)Thunderbolt USB-C Ports

Don't work, cause a lot of Kernel Panics. Disable them in BIOS. (Only affects ports that are both USB-C and Thunderbolt, regular USB-C work normally)

***

If you know more informations about some hardware compatibility that is not listed nere, or some information that is wrong, please open an issue at the repository page. If it helped you, save it with a star to help the project.
