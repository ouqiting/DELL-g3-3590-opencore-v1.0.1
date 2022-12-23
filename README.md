# Hackintosh-Dell-g3-15-3590<br>

## Laptop Specifications

Model     | Dell g3 15 3590 9<sup>th</sup> gen
---       | ---
Processor | Intel®️ Core™️ i5-9300H
iGPU      | Intel UHD 630
dGPU      | NVIDIA(R) GeForce(R) GTX 1650
Resolution| 15.6 inch FHD (1920 x 1080) 30 0 nits IPS Anti-Glare LED Back lit Display with 144Hz refresh rate
RAM       | 16GB, 2x8GB, DDR4 (2666MHz) 
Storage   | 128GB M.2 PCIe NVMe Solid State Drive (Boot) + 1TB 5400 rpm 2.5" SATA Hard Drive (Storage)
Audio     | Realtek ALC295
WIFI      | Intel AC9560 
Touchpad  | I2C1 HID TPD0
Bios      | 1.9.0 `Recommended`




## System configuration

Model | `MacBookPro16,4` | OS | `macOS Ventura` | OC | `0.8.4`
---|---|---|---|---|---

![](Images/about.png)


## what is working

✅  QE/CI Graphics Intel UHD 630 <br>
✅  Restart, Sleep and Shutdown (With and without Closing LID) <br>
✅  CPU Power Management <br>

---

✅  Internal speaker , headphone (with microphone)<br>

---



✅  Touchpad (SSDT Patche Interrupt GPIO Pinning) 'note that acpibattery.kext causes touchpad lag , using smcbatterymanager.kext fixed the issue' <br>


---

✅  Brightness (including f11 and f12) <br>
✅  Battery Indicator <br>
✅  Ethernet  
✅  Wifi <br>
✅  Bluetooth <br>


✅  All USB Port (including usb type c) <br>
✅  External Monitor work with type c cable <br>
✅  prtScr key disables touchpad & winKey + prtScr disables keyboard

## what is not working

❌  internal microphone (Smart Sound Technology is not supported by mac)<br>
❌  GTX 1650
