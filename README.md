

Building TWRP for Xiaomi Mi9 Lite

Working

ADB

Decryption userdata

Screen brightness settings

Correct screenshot color

MTP

To compile

build/envsetup.sh

export ALLOW_MISSING_DEPENDENCIES=true

lunch omni_pyxis-eng

make -jX recoveryimage
