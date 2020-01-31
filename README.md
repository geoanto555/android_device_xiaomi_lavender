Building TWRP for Xiaomi Redmi Note 7

Working

ADB

Decryption userdata

Screen brightness settings

Correct screenshot color

MTP

To compile

build/envsetup.sh

export ALLOW_MISSING_DEPENDENCIES=true

lunch omni_lavender-eng

make -jX recoveryimage
