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

# UV-K5-Modded-Firmwares
A collection of modified firmwares for the Quansheng UV-K5 radio.

*If you would like to build your own firmware with only the modifications that suit you, check out @amnemonic's excellent [uvmod-kitchen](https://github.com/amnemonic/Quansheng_UV-K5_Firmware/tree/main/uvmod_kitchen).*

This repository contains several firmwares, modified by:
- [@amnemonic](https://github.com/amnemonic)
- [@fagci](https://github.com/fagci)
- [@Tunas1337](https://github.com/Tunas1337)

Special thanks also goes to [@sq5bpf](https://github.com/sq5bpf) for his [work](https://github.com/sq5bpf/uvk5-reverse-engineering) in reverse engineering the communication protocols, frequency storage formats, memory maps and more.

Discussion of these firmwares, and other things related to the radio, can be done in the Telegram groups: [English](https://t.me/quansheng_uvk5_en), [Russian](https://t.me/uv_k5), [Spanish](https://t.me/QuanShengES), [Chinese.](https://t.me/uvk5cn)

You can support the authors with a donation at the following links:

Tunas1337:
[PayPal](https://www.paypal.com/donate/?business=C44RNB6MGGW26&no_recurring=0&item_name=If+you+like+my+work+on+adding+new+features+to+the+Quansheng+UV-K5%2C+I%27d+appreciate+your+support.&currency_code=USD)

The new features so far include, but are not limited to:
- Regular (FM) reception from 18-850MHz (1300MHz with the extended mod)
- AM reception from 18-136MHz (850MHz with the extended mod)
- Transmission outside of the 136-174,400-520MHz bands
