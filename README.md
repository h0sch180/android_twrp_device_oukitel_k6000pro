TWRP Device Tree for Oukitel K6000Pro 
===========
Unoffical Build for MT6753 TWRP 
------------------

the way to do:
```
- repo init -u git://github.com/minimal-manifest-twrp/platform_manifest_twrp_omni.git -b twrp-6.0

- repo sync

- git clone
  https://github.com/h0sch180/android_twrp_device_oukitel_k6000pro device/OUKITEL/K6000Pro

- . build/envsetup.sh

- lunch omni_K6000Pro-eng

- make -j# recoveryimage [# : no. of cpu core]
```

