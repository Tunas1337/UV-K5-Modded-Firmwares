# UV-K5-Modded-Firmwares
A collection of modified firmwares for the Quansheng UV-K5 radio.

This repository contains several firmwares, modified by:
- [@amnemonic](https://github.com/amnemonic)
- [@fagci](https://github.com/fagci)
- [@Tunas1337](https://github.com/Tunas1337)

Discussion of these firmwares, and other things related to the radio, can be done in the Telegram groups: [English](https://t.me/quansheng_uvk5_en), [Russian](https://t.me/uv_k5), [Spanish.](https://t.me/QuanShengES)

The new features so far include, but are not limited to:
- Regular (FM) reception from 18-850MHz (1300MHz with the extended mod)
- AM reception from 18-136MHz (850MHz with the extended mod)
- Transmission outside of the 136-174,400-520MHz bands

* **Warning:** The Quansheng UV-K5 CAN NOT receive signals between 630-840MHz. This is a hardware limitation of the Beken BK4819 baseband chip. Please do not open issues about this, it is impossible to fix in software.

# EVEN BIGGER WARNING
**This modification is UNTESTED and is for RESEARCH PURPOSES ONLY, to explore the capabilities of the device and its chipset. DO NOT transmit on illegal frequencies. DO use a dummy load. DO report results, preferably spectrum analyzer screenshots, to this repo for research. The author(s) and contributor(s) of this repository are NOT liable for any damages, litigation, or other consequences of the misuse of this research firmware and do not accept any culpability. By installing any firmware from this repository, you accept full responsibility for any consequences that may arise and waive the right to pursue legal action against the author(s).**

As an example against using this for actual communications, consider the following chart for transmission power for a transmission at 27.254MHz:
![photo_2023-06-05_16-09-50](https://github.com/Tunas1337/UV-K5-Modded-Firmwares/assets/12097904/21eca217-254d-4e9f-9558-6cf773a52a84)

- 27.254MHz -> **228 microwatts**
- 54 Mhz -> 2.4 milliwatts
- 81 Mhz -> 230 milliwatts
- 109 Mhz -> 558 milliwatts
- 136 Mhz -> 412 milliwatts
- 163 Mhz -> 122 milliwatts
- 190 Mhz -> 14.8 milliwatts
- 218 Mhz -> 2 milliwatts
- And finally, on 245 Mhz -> 2.6 milliwatts.
