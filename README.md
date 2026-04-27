<h1 align="center">
  <br>
  <a href="https://vejas.zip">
    <img width="max" height="200" alt="kaze_logo_kanji_center" src="https://github.com/user-attachments/assets/c35671ce-c6dd-45cb-86e6-3eb8ada3205e" />
  </a>
  <br>
  <sub>Kaze</sub>
  <br>
</h1>

<div align="center">
  <a href="https://kicad.org"><img src="https://img.shields.io/badge/KiCad-%23314CB0.svg?style=for-the-badge&logo=kicad&logoColor=white" alt="KiCad">
  <a href="https://www.espressif.com/en/products/socs/esp32"><img src="https://img.shields.io/badge/ESP32-%23E7352C.svg?style=for-the-badge&logo=espressif&logoColor=white" alt="ESP32"></a>
  <a href="https://www.home-assistant.io/"><img src="https://img.shields.io/badge/Home%20Assistant-%2341BDF5.svg?style=for-the-badge&logo=homeassistant&logoColor=white" alt="Home Assistant"></a>
  <a href="https://hackclub.com"><img src="https://img.shields.io/badge/Hack_Club-%23EC3750?style=for-the-badge&logo=hackclub&logoColor=white"></a>
</div>

<h4 align="center">An all-in-one ambient sensor for <a href="https://www.home-assistant.io/">Home Assistant</a>, powered by the ESP32-C6.</h4>

<br>

## Overview

Kaze is a compact ambient sensor that measures a wide range of environmental data and exposes it to Home Assistant via ESPHome. It supports **Zigbee, Wi-Fi, Bluetooth, and Thread** out of the box thanks to the ESP32-C6 module.

## Sensors

| Sensor | Measurements |
|--------|-------------|
| BME680 | Temperature, Humidity, Pressure, CO₂ / AQI |
| TSL25911FN | Illuminance (lux), IR |
| WS2812B | RGB status LED |

## Connectivity

The ESP32-C6-MINI-1 module provides:
- Wi-Fi
- Bluetooth 5
- Thread / Matter
- Zigbee

These will be utilised to connect to your Home Assistant setup and provide temperature readings.


## Software

Firmware is written for **ESPHome**, making it seamless to integrate with Home Assistant. *(Work in progress)*

## Images

<p align="center">
  <img src="./images/SCR-20260110-qhxa.png" width="49%">
  <img src="./images/SCR-20260110-qida.png" width="49%">
  <img src="./images/SCR-20260110-qiew.png" width="49%">
  <img src="./images/SCR-20260110-qihw.png" width="49%">
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/e685ba49-f509-4b24-87f6-ac48782506c7" width="100%">
</p>

## Bill of Materials

### JLCPCB

| Item | Cost |
|------|------|
| PCB (5×) | $2.10 |
| Stencil | $7.00 |
| Shipping (Global Standard Direct Line) | $26.55 |

### LCSC Components

| Part | Mfr. | Qty | Unit Price | Ext. Price | LCSC# |
|------|------|-----|------------|------------|-------|
| ESP32-C6-MINI-1-N4 | Espressif | 2 | $4.04 | $8.09 | [C5736265](https://www.lcsc.com/product-detail/C5736265.html) |
| BME680 | Bosch | 1 | $9.85 | $9.85 | [C125972](https://www.lcsc.com/product-detail/C125972.html) |
| TSL25911FN | AMS | 3 | $1.81 | $5.42 | [C176812](https://www.lcsc.com/product-detail/C176812.html) |
| MCP73831T-2ACI/OT | Microchip | 2 | $0.73 | $1.46 | [C424093](https://www.lcsc.com/product-detail/C424093.html) |
| AP2112K-3.3TRG1 (LDO 3.3V) | Tech Public | 5 | $0.09 | $0.47 | [C23380830](https://www.lcsc.com/product-detail/C23380830.html) |
| WS2812B-2020 (RGB LED) | Worldsemi | 10 | $0.08 | $0.83 | [C965555](https://www.lcsc.com/product-detail/C965555.html) |
| USB-C Receptacle 16P | Shou Han | 20 | $0.06 | $1.20 | [C2765186](https://www.lcsc.com/product-detail/C2765186.html) |
| Tactile Switch SPST | Alps Alpine | 5 | $0.13 | $0.65 | [C115357](https://www.lcsc.com/product-detail/C115357.html) |
| Cap 100nF 0402 | Samsung EM | 100 | $0.005 | $0.49 | [C16193311](https://www.lcsc.com/product-detail/C16193311.html) |
| Cap 4.7µF 0402 | Samsung EM | 20 | $0.009 | $0.18 | [C318563](https://www.lcsc.com/product-detail/C318563.html) |
| Cap 10µF 0402 | Samsung EM | 50 | $0.012 | $0.59 | [C3902158](https://www.lcsc.com/product-detail/C3902158.html) |
| Cap 1µF 16V 0402 | Samsung EM | 100 | $0.002 | $0.23 | [C29266](https://www.lcsc.com/product-detail/C29266.html) |
| Cap 1µF 10V 0402 | Samsung EM | 100 | $0.002 | $0.18 | [C14445](https://www.lcsc.com/product-detail/C14445.html) |
| Res 10kΩ 0402 | Yageo | 100 | $0.001 | $0.07 | [C60489](https://www.lcsc.com/product-detail/C60489.html) |
| Res 4.7kΩ 0402 | Yageo | 100 | $0.001 | $0.07 | [C105870](https://www.lcsc.com/product-detail/C105870.html) |
| Res 2.4kΩ 0402 | Yageo | 100 | $0.001 | $0.07 | [C137889](https://www.lcsc.com/product-detail/C137889.html) |
| Res 5.1kΩ 0402 | Yageo | 100 | $0.001 | $0.08 | [C105872](https://www.lcsc.com/product-detail/C105872.html) |
| Res 22Ω 0402 | Yageo | 100 | $0.001 | $0.07 | [C114765](https://www.lcsc.com/product-detail/C114765.html) |

### Other

| Item | Cost |
|------|------|
| LiPo Battery 3.7V 800mAh (802540) | $6.52 |
| LCSC Shipping | $9.50 |

### 💰 Total Cost Estimate

| | |
|---|---|
| LCSC components + shipping | ~$38.00 |
| JLCPCB PCB + stencil + shipping | ~$35.65 |
| Battery | $6.52 |
| Discounts | −$5.10 |
| **Total** | **~$76.67** |

> Shipping cost for JLCPCB can be roughly halved if ordered alongside another project.
