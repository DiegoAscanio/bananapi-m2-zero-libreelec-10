# Banana PI M2 Zero LibreElec 10 Image

What works:

- WiFi
- Audio (through HDMI)
- Video
  - YouTube (480p quality)
  - HBO Max (480p quality)
  - Netflix and Prime Video (probably)

What don't:

- Bluetooth

Not tested:

- PVR / IPTV, LibRetro Emulators

My effusive thanks to [@jernejsk](https://github.com/jernejsk) who made this build possible by adding H2+ platform at LibreElec10's Supported Devices.

## How to install it (Linux):

1. Download the [gzip image](https://github.com/DiegoAscanio/bananapi-m2-zero-libreelec-10/raw/main/LibreELEC-H2-plus.arm-10.0-devel-20210810184355-beaa0c7-bananapi-m2-zero.img.gz) above
2. Insert an SD Card at your computer
3. Unmount any SD Card partitions:

    `sudo umount mmcblk0p*`
    
4. Extract LibreElec10's img file:

    `gunzip LibreELEC-H2-plus.arm-10.0-devel-20210810184355-beaa0c7-bananapi-m2-zero.img.gz`

5. Flash it to SD card with `dd`:

    `sudo dd if=LibreELEC-H2-plus.arm-10.0-devel-20210810184355-beaa0c7-bananapi-m2-zero.img of=/dev/mmcblk0`

## License (Disclaimer)

As this image is a [LibreElec](https://github.com/LibreELEC)'s build, it's licensed under their GPLv2's [license](https://github.com/LibreELEC/LibreELEC.tv/tree/master/licenses), under their terms and all copyrights belong to them.
