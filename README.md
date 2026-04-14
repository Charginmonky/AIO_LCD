# AIO_LCD

A custom-built LCD for a PC's Thermalright AIO that displays images, GIFs, videos, or the time, giving the AIO a more premium and functional look.

## Overview

- **Host PC → WiFi → Raspberry Pi Zero 2 W → HDMI driver → Round LCD**
- Upload content from the PC (image / GIF / MP4).
- Pi stores the last uploaded file and auto-plays it on boot.
- If nothing is uploaded, the screen stays black (no desktop, no UI).

## Features

- Looping playback for GIFs and MP4s.
- Last-content resume on boot.
- Simple HTTP upload endpoint on the Pi.
- Minimal PC-side uploader script.
- Designed for clean internal mounting in an AIO shroud.


## 3D Models
<img width="708" height="707" alt="Screenshot 2026-04-14 220126" src="https://github.com/user-attachments/assets/e0fc214a-b344-444d-bdd9-e87fea0de602" />
<img width="726" height="666" alt="Screenshot 2026-04-14 220135" src="https://github.com/user-attachments/assets/4039dec5-ca4f-4c6b-b176-90956064c3c1" />
<img width="473" height="573" alt="Screenshot 2026-04-14 220157" src="https://github.com/user-attachments/assets/b3b22af2-eb5c-4a63-af2e-3723074e10fb" />
<img width="568" height="596" alt="Screenshot 2026-04-14 220328" src="https://github.com/user-attachments/assets/f0d53896-d6f6-44da-bece-3a15238dcc32" />
<img width="580" height="479" alt="image" src="https://github.com/user-attachments/assets/8523de52-02d2-4e8e-a98f-46a7beb90a79" />

## BOM

| Item                       | Description                               | Qty | Price  | Link |
|---------------------------|-------------------------------------------|-----|--------|------|
| Mini‑HDMI cable           | Ultra‑thin HDMI cable for Pi → LCD        | 1   | £3.28  |[LINK](https://www.aliexpress.com/item/1005010428345434.html)|
| Micro‑USB cable           | Power delivery for Pi and LCD             | 2   | £0.75  |[LINK](https://www.aliexpress.com/item/1005006135009963.html)|
| Raspberry Pi Zero 2W      | Computer that drives the LCD              | 1   | £14.40  |[LINK](https://thepihut.com/products/raspberry-pi-zero-w?variant=31901049749566&country=GB&currency=GBP&utm_medium=product_sync&utm_source=google&utm_content=sag_organic&utm_campaign=sag_organic&gad_source=1&gad_campaignid=11284298573&gclid=CjwKCAjwnN3OBhA8EiwAfpTYevEBa2KHGgwrYWmlaEMBvTMTWnJW67xdDjyH5iX81vgLJoVPeRDztxoCtM0QAvD_BwE)|
| 9‑Pin to Dual USB Adapter | Adapter for motherboard → USB power       | 1   | £0.76  |[LINK](https://www.aliexpress.com/item/1005008162615589.html)|
| LCD                       | Display for AIO                           | 1   | £30.99 |[LINK](https://www.aliexpress.com/item/1005011869877146.html)|
|TOTAL                        |                                           |    | £50.18 |      

