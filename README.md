# i.MX8-Atlas
 
A small-form-factor alternative to the NXP iMX8M Plus development board. 
Some interfaces were trimmed to reduce cost and board space - one HDMI instead of two, single CSI camera, LVDS channel 0 only. The result is a clean 6-layer design with 4GB of RAM that can be fabricated at JLCPCB for under £100 (excluding RAM 💸).

 ![iMX8 - Atlas](https://github.com/ADubovitskiy/i.MX8-Atlas/blob/main/Galery/iMX%208%20Atlas.png) "Image 1 - Top Layer"
 
## Main System Blocks
| | |
|---|---|
| **Processor** | NXP i.MX 8M Plus — quad Cortex-A53 + Cortex-M7 + NPU |
| **Memory** | 4GB LPDDR4 (Micron MT53E1024M32D4DE) |
| **Storage** | eMMC 5.1 + 32MB QSPI NOR Flash |
| **Ethernet** | Realtek RTL8211F-CG GbE PHY |
| **PMIC** | NXP PCA9450C |
| **Form factor** | SoM + carrier board via 2× 70-pin mezzanine connectors |
| **PCB** | 6-layer, JLC06161H-1080A stackup, 1.2mm |

## Connectors
 
Two 70-pin mezzanine connectors expose all carrier-facing signals.
 
**Connector 1** — Control & digital: UART ×3, I²C ×3, SPI, CAN FD ×2, SAI3 audio, PCM/BT, SPDIF, SD1/2, HDMI, Ethernet MDI, GPIO, Reset/Boot, 5V power in.

**Connector 2** — High-speed differential: LVDS0, MIPI DSI, MIPI CSI1, USB1+2 (SuperSpeed), PCIe Gen3 ×1.
 
---
 
## Component Placement
 
> *Image coming soon*
 
---
 
## Stackup
 
**JLCPCB JLC06161H-1080A · 6 layers · 1.2mm**
 
> *Image coming soon*
