# Hackintosh Compatibility Chart
 This repository contains informations about hardware compatibility with hackintosh

## CPU Compatibility
### Intel Desktop
CPU Generation/macOS Version | Tiger | Leopard | Snow Leopard | Lion | Mountain Lion | Mavericks | Yosemite | El Capitain | Sierra | High Sierra | Mojave | Catalina | Big Sur | Monterrey | Ventura | Sonoma | Sequoia
---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---|---
**Intel Yonah, Conroe and Penryn(Core and Core 2)** | ✅¹ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️² | ⚠️³ | ⚠️³ | ⚠️³ | ⚠️³| ⚠️³ | ⚠️³ | ⚠️³   
**Intel Lynnfield and Clarkdale(1st)** | 🚫 | 🚫 | ✅⁴ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️³ | ⚠️³ | ⚠️³
**Intel Sandy Bridge(2nd)** | 🚫 | 🚫 | ✅⁵ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️³ | ⚠️³ | ⚠️³
**Intel Ivy Bridge(3rd)** | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ⚠️³ | ⚠️³ | ⚠️³
**Intel Haswell(4th and 5th)** | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅
**Intel Skylake(6th)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅
**Intel Kaby Lake(7th)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅
**Intel Coffee Lake(8th and 9th)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅
**Intel Comet Lake (10th)** | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | 🚫 | ✅ | ✅ | ✅ | ✅ | ✅ | ✅

>¹ Starts at Mac OS X Tiger 10.4.10

>² As Yonah and Conroe CPUs don't support SSE4, they can only boot up to Sierra. Penryn does support SSE4, so it works natively with High Sierra

>³ Old CPUs support for newer versions of macOS may require OpenCore Legacy Patcher or CryptexFixup kext (CPUs that don't support AVX2)

>⁴ Starts at OS X Snow Leopard 10.6.3

>⁵ Starts at OS X Snow Leopard 10.6.7
