# Samsung Chromebook 4 / 4+ Project
 
## Purpose
 
Notes and findings from converting a Samsung Chromebook 4+ to alternative operating systems. This project is mainly focused on extending the life of low-end Chromebook hardware through Linux and Windows installations.
 
Test Device
 
**Samsung Chromebook 4+**
 
- Intel Celeron N4020
- 6GB LPDDR4 RAM
- 64GB eMMC Storage
 
---
 
Tools Required
 
- Charger
- Precision screwdriver set
- Plastic prying tool
- USB drive for installation media
- ESD protection (recommended)
 
A prying tool is recommended to avoid breaking the plastic clips that hold the bottom cover in place.
 
---
 
Disassembly
 
1. Power off the Chromebook.
2. Remove all bottom screws (some may be hidden under the rubber feet).
3. Carefully remove the bottom cover.
4. Disconnect the battery if needed.
 
---
 
Write Protection
 
Unlike older Chromebooks, newer models typically do not use a write-protection screw.
 
On my Chromebook 4+, I was able to bypass write protection by:
 
1. Disconnecting the battery.
2. Connecting the charger.
3. Booting on AC power only.
4. Proceeding with firmware and OS modifications.
 
**Use caution when modifying firmware. There is always a risk of bricking the device.**
 
---
 
Operating System Options
 
### Linux
 
Linux is easily the best option for this hardware.
 
Tested or recommended distributions:
 
- Linux Mint XFCE
- Lubuntu
- Xubuntu
- Debian XFCE
- MX Linux
 
Pros:
 
- Better performance
- Lower memory usage
- No licensing costs
- Better use of limited storage
 
**Recommendation: Yes**
 
### Windows 11
 
Installed as an experiment.
 
Issues encountered:
 
- Audio drivers not detected
- Coolstar audio packages did not work on my unit
- Higher resource usage
- More troubleshooting than it was worth
 
**Recommendation: No**
 
### Windows 10
 
More usable than Windows 11.
 
Issues encountered:
 
- Unknown devices still present in Device Manager
- Driver troubleshooting required
- Audio support may vary
 
Usable for basic tasks, but still not ideal.
 
**Recommendation: Only if you need Windows**
 
---
 
## Final Thoughts
 
The Chromebook 4/4+ is limited by its N4000/N4020 processor, small amount of RAM, and eMMC storage, but it is still perfectly usable for web browsing, office work, programming, and general daily tasks.
 
If you're considering an OS conversion, a lightweight Linux distribution provides the best overall experience with the least amount of troubleshoo
