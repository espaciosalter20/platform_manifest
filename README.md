manifests to build Android 4.4 for Xiaomi Mi2/2S

How to build MI2/2S:
-------------

Initialize repo:

    repo init -u git://github.com/espaciosalter20/platform_manifest
    repo sync

    . build/envsetup.sh && lunch aries-userdebug

    make otapackage -j16
