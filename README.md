## TWRP Device Tree for the Galaxy S5 Mini Qualcomm (SM-G800H, kmini3g)

### How to build
1. Get the 
[minimal-manifest-twrp](https://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni/tree/twrp-7.1)
(omni twrp-7.1 branch) and follow the instructions there

2. Clone this repository to `device/samsung/kmini3g`
```
git clone https://github.com/prototype74/android_device_samsung_kmini3g.git -b android-7.1 device/samsung/kmini3g
```

3. Build the recovery image
```
. build/envsetup.sh; lunch omni_kmini3g-eng; mka recoveryimage
```
### Kernel source
[https://github.com/prototype74/android_kernel_samsung_msm8226/tree/twrp-7.1](https://github.com/prototype74/android_kernel_samsung_msm8226/tree/twrp-7.1)

