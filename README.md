## Recovery Device Tree for the Samsung Galaxy M51 (Snapdragon)

## How-to compile it:

```sh
export ALLOW_MISSING_DEPENDENCIES=true
. build/envsetup.sh
lunch twrp_m51-eng
make recoveryimage
```

Kernel source:
https://github.com/mohammad92/android_kernel_samsung_m51
