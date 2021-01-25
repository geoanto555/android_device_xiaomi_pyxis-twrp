![Xiaomi Mi 9 Lite](https://fdn2.gsmarena.com/vv/pics/xiaomi/xiaomi-mi-9-lite-1.jpg "Mi 9 Lite")

=====================================================
Basic   | Specs
-------:|:-------------------------
CPU     | Qualcomm SDM710 Snapdragon 710 (10 nm)
GPU     | Adreno 616
Memory  |  6GB
Storage | 64GB 128GB
Os      | Android 9, MIUI 11
Battery | Li-Po 4030 mAh, non-removable,Fast charging 18W
Dimensions | 156.8 x 74.5 x 8.7 mm (6.17 x 2.93 x 0.34 in)
Display |  6.39 inches, 1080 x 2340 pixels, 19.5:9 ratio 
Rear Camera  | 48 MP, f/1.8, (wide), 1/2.0", 0.8µm, PDAF
<<        >> | 8 MP, (ultrawide), 1/4.0", 1.12µm
<<        >> | 2 MP, (depth)
Front Camera | 32 MP, f/2.0, 26mm (wide), 1/2.8", 0.8µm
Release Date |  2019, September 16

------------------------------------

Building TWRP for Xiaomi Mi9 Lite

## Working :

- ADB

- Decryption userdata

- Screen brightness settings

- Correct screenshot color

- MTP

## To compile

- build/envsetup.sh

- export ALLOW_MISSING_DEPENDENCIES=true

- lunch omni_pyxis-eng

- make -jX recoveryimage
