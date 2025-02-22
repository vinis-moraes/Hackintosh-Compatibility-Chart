# Hackintosh Compatibility Chart
 This repository contains informations about hardware compatibility with hackintosh

## CPU Compatibility
### Intel Desktop
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

### Intel Laptop

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
**Whiskey Lake(8th)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅⁷ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ 
**Coffee Lake Plus(9th)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ 
**Comet Lake(10th)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ 
**Ice Lake(10th)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ 


> _Due to the fact that most laptops rely only on Integrated Graphics, check GPU Compatibility. Most iGPUs can be used with OpenCore Legacy Patcher to provide support for newer OS releases_

>³ Old CPUs support for newer versions of macOS may require OpenCore Legacy Patcher or CryptexFixup kext (CPUs that don't support AVX2)

>⁶ CPU is supported, but iGPU is not. Use OpenCore Legacy Patcher to have Graphics Acceleration

>⁷ Starts at macOS 10.14.1

### Intel HEDT (High End Desktop)

CPU Generation/macOS Version | Tiger (10.4) | Leopard (10.5) | Snow Leopard (10.6) | Lion (10.7) | Mountain Lion (10.8) | Mavericks (10.9) | Yosemite (10.10) | El Capitain (10.11) | Sierra (10.12) | High Sierra (10.13) | Mojave (10.14) | Catalina (10.15) | Big Sur (11) | Monterrey (12) | Ventura (13) | Sonoma (14) | Sequoia (15)
---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---
**Nehalem and Westmere** | 🚫 | ✅⁸ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️³ | ⚠️³ | ⚠️³
**Sandy and Ivy Bridge-E** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️³ | ⚠️³ | ⚠️³
**Haswell-E** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅
**Broadwell-E**  | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅
**Skylake-X/W and Cascade Lake-X/W** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ 

### AMD Desktop

CPU Generation/macOS Version | Tiger (10.4) | Leopard (10.5) | Snow Leopard (10.6) | Lion (10.7) | Mountain Lion (10.8) | Mavericks (10.9) | Yosemite (10.10) | El Capitain (10.11) | Sierra (10.12) | High Sierra (10.13) | Mojave (10.14) | Catalina (10.15) | Big Sur (11) | Monterrey (12) | Ventura (13) | Sonoma (14) | Sequoia (15)
---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---
**Bulldozer and Jaguar** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️³ | ⚠️³ | ⚠️³
**Ryzen and Threadripper** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅

>³ Old CPUs support for newer versions of macOS may require OpenCore Legacy Patcher or CryptexFixup kext (CPUs that don't support AVX2)

### AMD Laptop

CPU Generation/macOS Version | Tiger (10.4) | Leopard (10.5) | Snow Leopard (10.6) | Lion (10.7) | Mountain Lion (10.8) | Mavericks (10.9) | Yosemite (10.10) | El Capitain (10.11) | Sierra (10.12) | High Sierra (10.13) | Mojave (10.14) | Catalina (10.15) | Big Sur (11) | Monterrey (12) | Ventura (13) | Sonoma (14) | Sequoia (15)
---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---
**Ryzen** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅

>The OpenCore Team does not provide guides to build Ryzentoshes on laptops. On the other side, there are reports of various succesful builds using laptops with Ryzen and Integrated Graphics over the Internet

## Graphics Compatibility

### NVIDIA support

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

### AMD/ATI support

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
**Navi 23(RX 66**)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅¹⁴ | ✅ | ✅ | ✅

>⁹ Legacy AMD/ATI GPUs need OpenCore Legacy Patcher to work on newer versions of macOS

>¹⁰ Starts at 10.12.6

>¹¹ Starts at 10.14.5

>¹² Starts at 10.15.1

>¹³ Starts at 11.4

>¹⁴ Starts at 12.1