<div align="center">

# fogos-5.4

<p align="center">
  <img src="profile/banner.png">
</p>


Device development for the Motorola moto g34 5G and moto g45 5G — codename `fogos`

<img alt="platform" height="24" src="https://img.shields.io/badge/platform-SM6375%20holi-8BC34A?style=flat-square&amp;logo=snapdragon&amp;logoColor=white">

<img alt="kernel" height="24" src="https://img.shields.io/badge/kernel-5.4-FCC624?style=flat-square&amp;logo=linux&amp;logoColor=black">

<img alt="repositories" height="24  " src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fapi.github.com%2Forgs%2Ffogos-5-4&amp;query=public_repos&amp;label=repos&amp;style=flat-square&amp;logo=github&amp;logoColor=white&amp;color=E75480">

</div>

---

## Overview

This organization brings together the complete source code ecosystem for **Android 16 and Android 17** across the **Motorola moto g34 5G and moto g45 5G**.

Both devices share the `fogos` codename and are built on Qualcomm's **SM6375 (`holi`) platform**, allowing them to leverage a unified device tree and a shared foundation for Android development.

The repositories cover the essential components required for building, maintaining, and developing Android-based ROMs for the `fogos` platform.

## Device

| | moto g34 5G | moto g45 5G |
| --- | --- | --- |
| SoC | Snapdragon 695 5G | Snapdragon 6s Gen 3 (SM6375-AC) |
| Platform | SM6375 `holi`, 6 nm | SM6375 `holi`, 6 nm |
| CPU / GPU | Octa-core Kryo 660 · Adreno 619 | Octa-core Kryo 660 · Adreno 619 |
| Architecture | `arm64`, `armv8-2a-dotprod` | `arm64`, `armv8-2a-dotprod` |
| Display | 6.5″ IPS LCD, 720 × 1600, 120 Hz | 6.5″ IPS LCD, 720 × 1600, 120 Hz |
| Memory / storage | 4–8 GB LPDDR4X · UFS 2.2 | 4–8 GB LPDDR4X · UFS 2.2 |
| Camera | 50 MP f/1.8 + 2 MP macro · 16 MP front | 50 MP f/1.8 + 2 MP macro · 16 MP front |
| Battery | 5000 mAh, TurboPower | 5000 mAh, TurboPower |
| Audio | Stereo, Dolby Atmos, 3.5 mm jack | Stereo, Dolby Atmos, 3.5 mm jack |


## Branch naming

 - Branch **lineage-23.2** is for android 16.
 - Branch **17.0** is for android 17
 - Any other branches with custom rom name's holds there respective bringups as the latest android version they are giving

## Credits

 - Special thanks to Lineage Team for the base tree,kernel and hardware hals.
 - Special thanks to the **TheMuppets** for vendor.
 - Special thanks to **Moto-Sedona** **Motorola-SM6375-Devs** for varoius improvement and fixes.
 - Thanks to all contributers for there works. 

## Disclaimer

```c
/*
 * Your warranty is now void.
 *
 * I am not responsible for bricked devices, dead SD cards, thermonuclear war,
 * or you getting fired because the alarm app failed. Please do some research
 * if you have any concerns about features included in this ROM before
 * flashing it. YOU are choosing to make these modifications, and if you point
 * the finger at me for messing up your device, I will laugh at you.
 */
```

Motorola, moto g34 and moto g45 are trademarks of Motorola Trademark Holdings, LLC.
This project is not affiliated with or endorsed by Motorola or Lenovo.
