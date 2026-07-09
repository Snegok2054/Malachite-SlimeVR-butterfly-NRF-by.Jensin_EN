# 🦋 Malachite Tracker Cases

> A complete English guide for building **Malachite Trackers** based on the **nRF52840 + LSM6DSV** platform.
>
> This repository contains everything you need to build reliable and lightweight SlimeVR trackers, including a printable case, assembly instructions, firmware setup, and recommended components.

---

<img width="2560" height="1327" alt="Malachite Tracker" src="https://github.com/user-attachments/assets/ec5450a6-041d-4c87-b6ea-08662443c785" />

# 📖 Table of Contents

- [🧰 Required Materials](#-required-materials)
- [🔧 Tools](#-tools)
- [🖨️ Printing the Case](#️-printing-the-case)
- [🔌 Soldering](#-soldering)
- [💻 Firmware Installation](#-firmware-installation)
- [✅ Function Test](#-function-test)
- [🛠️ Assembly](#️-assembly)
- [📊 Specifications](#-specifications)
- [❤️ Credits](#️-credits)

---

# 🧰 Required Materials

## 🖨️ PETG Filament

I highly recommend printing the case using **PETG**. It offers excellent durability, impact resistance, and is well suited for wearable tracker enclosures.

---

## 🖨️ TPU-95A Filament

Used for printing the flexible connector.

---

## 📟 ProMicro nRF52840

An affordable microcontroller that includes everything required for running SlimeVR trackers.

---

## 📡 LSM6DSV IMU

In my opinion, this currently provides the best **price-to-performance ratio** available.

---

## 🔩 DIN7991 M2.5 × 8 mm Screws

Required for securing the enclosure.

---

## 🔋 601730 Li-Po Battery

After testing several options, I found this battery size to provide an excellent balance between capacity, size, and weight.

---

## 📶 Holyiot Dongle

Required for wireless communication between the trackers and your PC.

---

## 🔘 SMD Push Button (3 × 4 × 2 mm, 2-Pin)

Used as the tracker power button.

---

# 🔧 Tools

You will need the following tools:

- 🖨️ An FDM 3D printer with a **0.4 mm nozzle** (or smaller).

  If you don't own a printer, you can simply use a local 3D printing service.

> I personally printed these parts using an **Anycubic S1 Combo**.

---

- ✂️ Side cutters

Can be replaced with a lighter for stripping wires, although this increases the risk of damaging the battery.

---

- 🔥 Soldering iron

Almost any soldering iron will work.

> I personally use the **Alientek T90B**.

---

- 🧲 Tweezers

Recommended:

- Standard metal tweezers
- Ceramic tweezers (optional)

Ceramic tweezers are useful if you're worried about accidentally shorting nearby contacts.

---

- 🔧 1.5 mm Hex Key

I use a Xiaomi precision screwdriver kit.

---

- 📏 File

The **nRF52840** board fits the enclosure very tightly.

Before assembly, lightly file the edges of the PCB until it slides into the case smoothly.

---

# 🖨️ Printing the Case

If you ordered the printed parts from someone else, you can safely skip to the **Soldering** section.

If you're printing the parts yourself, no special slicer settings are required.

Simply:

1. Import the models.
2. Rotate each part into the correct orientation.
3. Start the print.

<img width="1328" height="950" alt="Slicer Preview" src="https://github.com/user-attachments/assets/6742bbff-d35b-43a6-aba7-bb7272f79481" />

---

# 🪡 Sewing Strap

## We cut the required number of straps of the required length
>*(You can view the location of the trackers in the SlimeVR software.)*

## We scorch the ends so that the straps do not fluff
<img width="2560" height="1215" alt="y3T4tMG_LVLqBQYx1nWbwtsXEmMVPN6toz46hCMsqMB2w4NiKQfy06ude4UrgFSEDOulrklT21wuZQ2gDXGnMQuz" src="https://github.com/user-attachments/assets/e0c72431-c454-4f86-afc1-e38721b8ba68" />

## We thread the belt as shown in the photo
<img width="2560" height="1109" alt="cKdN3GMzgc_l1ebIV0I79vQ-arx-Q_xZlx25gda4rHTl53xAPOIxhW1_Oh2zc4tjdRTlawKSHHo8g1oUZtxZee4q" src="https://github.com/user-attachments/assets/a2f77e38-895c-438e-9ff8-801e3d227318" />

## And we sew it. It should turn out like this
<img width="2560" height="1385" alt="-KGbGSolIeY92IAmkcOYHnFcdgYZ969AVWoKmeNcH7Ktw5pC_4w0Rq7-_QU3OBAsdNzlwWBXinQR0kQEWAv9mdic" src="https://github.com/user-attachments/assets/eedf6130-d4da-401a-b996-0e5aa95cce34" />


## We thread one of the parts of the swallow as in the photo.
<img width="2560" height="1227" alt="SyZeXxIdC8ZUTsQgwde07MwIuZt_h9UHVgdZSPAlJ8CRoUEaG7mhuIZlIZWH_eaMzyI05XTFCnEdagPeriF4-de5" src="https://github.com/user-attachments/assets/0d8648b3-d5ab-457f-ac2b-6c7b4b02caa3" />


## We drive it right up to the regulator as in the photo
<img width="1920" height="2560" alt="wl2P6CzsVXmvVIzgOzDiRVwiKuqabrsclgcsGOHqBLmyl2lXoN1YbCBU7YRULHU9ktjjHzMuKzIz4RolyRX515El" src="https://github.com/user-attachments/assets/579267a2-5a49-4773-b712-00a57e56aa3c" />


## Then we thread the Free end of the belt into the regulator
<img width="2560" height="1243" alt="Y_YZt_pFJbzYjt00edKEzPy4oL47cQv5HMwAUtoIOYx9e9nq3YJy925gXTD8UukXojsXKELx1oJ3zp1ARIIqCCLV" src="https://github.com/user-attachments/assets/12ae72f4-32a4-4735-bacb-5356378a20b7" />


## We try on the second part of the swallow and sew it
<img width="2560" height="1259" alt="Fz6fd-qzPimQiZDT4KocnytDDIOlN4Ex1UdvRxafme-UsyvEOR2Cd0y208s0_EMs9_mIqIlohCuSCPSZtYaUM-tQ" src="https://github.com/user-attachments/assets/e35a1331-50e2-4519-86ac-e482c502c75b" />


# Congratulations, your belt is ready! We do this the right number of times.
<img width="1920" height="2560" alt="rDI6puFXpZfY8mgi_SOeIOVgbmyzjESMNKTNR8nULYsud6zxAWut83PL6xczsUEiX7Sr7UXENXTROC6yMwKYIjcz" src="https://github.com/user-attachments/assets/ddf32116-c68e-4755-9c17-f079a8253478" />


---

# 🔌 Soldering

## 🎥 Video

> *(A soldering tutorial video will be added here in the future.)*

---

# 💻 Firmware Installation

This was by far the most challenging part of the entire build.

You'll need the following software:

### [SmolSlimeConfigurator (SSC)](https://github.com/ICantMakeThings/SmolSlimeConfigurator/tree/main?tab=readme-ov-file)

Used for:

- Flashing the trackers
- Pairing the trackers with the dongle
- Configuring and calibrating the devices

---

### nRF Connect

Unfortunately, **SSC currently cannot flash the Holyiot Dongle**, so you'll need **nRF Connect** for that step.

---

### Possible Issue

If **nRF Connect** doesn't allow you to install the **Programmer** plugin, you'll also need to install **nRF Util**.

To save others from spending hours searching for working downloads, I've prepared a release containing all the required software.

If you prefer, you can always download everything directly from the official sources.

> I personally lost a lot of time because of outdated or broken download links, so I wanted to mention this in advance.

---

# ✅ Function Test

Before assembling the tracker completely, verify the following:

- ✅ Every solder joint is clean and solid.
- ✅ All flux residue has been removed.
- ✅ The battery polarity is correct.
- ✅ The IMU is detected successfully.
- ✅ The tracker flashes without errors.
- ✅ The dongle recognizes the tracker.

---

# 💡 Tips

- Keep solder joints as small as possible.
- The push button should not protrude beyond the PCB.
- Mount the IMU as straight and level as possible.
- Always test the tracker before final assembly.

---

# 🛠️ Assembly

> *(Assembly photos and a detailed step-by-step guide will be added soon.)*

---

# 📊 Specifications

| Parameter | Value |
|-----------|-------|
| Dimensions | **61 × 40 × 8 mm** |
| Weight | **21 g** |
| Battery Life | **50+ hours** |

---

# ❤️ Credits

## Snegok

- Soldering
- English translation
- Project documentation

---

## [itsJensin](https://github.com/itsJensin)

- 3D modeling
- Case design
- Original English guide for the [Mochi V4](https://github.com/itsJensin/Malachite-Tracker-Cases-For-Mochi)

Special thanks for patiently answering my endless questions over the past two months. 😄

---

# 🚀 Final Notes

This project took a long time to complete, but I genuinely enjoyed every step of the process.

In my opinion, this is currently one of the best **Butterfly-style** cases available for SlimeVR trackers.

A matching **charging dock / travel case** is already in development and will be released soon.

---

# 📄 License

The author permits the free use of the contents of this repository **for personal and non-commercial purposes only**.

## ✅ You May

- Use the project files for personal use.
- Print and assemble trackers for yourself.
- Study, modify, and adapt the project to your own needs.
- Publish photos, videos, reviews, or other content featuring this project **provided that proper credit is given to the author along with a link to this repository.**

---

## ❌ You May Not

- Manufacture parts, enclosures, or complete devices based on this project **for sale or any commercial purpose**.
- Sell the digital files, 3D models, modified versions, or derivative works without written permission from the author.
- Use any part of this project for commercial purposes without prior written approval.

---

## 📝 Attribution

If you publish any content related to this project (including photos, videos, articles, reviews, or tutorials), you must include:

- The author's name.
- A link to this GitHub repository.

Example:

> **Malachite Tracker Case** by **Snegok**
>
> https://github.com/Snegok2054/Malachite-Tracker-Cases-For-Nrf52840-by.JENSIN/tree/main

---

## ⚖️ Commercial Use

If you would like to use this project for manufacturing, selling products, providing printing services, or any other commercial activity, you must obtain written permission from the author before doing so.
```
