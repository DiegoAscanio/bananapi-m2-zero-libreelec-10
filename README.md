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

1. Download the gzip image above
2. Insert an SD Card at your computer
3. Unmount any SD Card partitions:
  #umount mmcblk0p*
4. Extract LibreElec10's img file
  gunzip LibreELEC-H2-plus.arm-10.0-devel-20210810144215-beaa0c7-bananapi-m2-zero.img.gz
5. Flash it to SD card with `dd`:
  #dd if=LibreELEC-H2-plus.arm-10.0-devel-20210810144215-beaa0c7-bananapi-m2-zero.img of=/dev/mmcblk0

## License (Disclaimer)

As this image is a LibreElec's build, it's licensed under their GPLv2's license, under their terms and all copyrights belong to them.
