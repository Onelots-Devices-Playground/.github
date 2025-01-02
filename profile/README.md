# Organization for playing with My devices. Where I'll do my tests basically.

Owned : 
- Google Pixel 3a (Sargo)
- Xiaomi Mi Mix 2s (Polaris)
- Xiaomi Redmi 5 Plus (Vince)
- Oneplus 5 (CheeseBurger)
- Oneplus 5T (HotDogB)
- Xiaomi Redmi Note 11 Pro 5G (Veyx)


# Vince :

```xml
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
    <remote name="vince" fetch="https://github.com/Xiaomi-Redmi-5-Plus-developement/" revision="lineage-21" />

    <!-- Device Tree -->
    <project name="device_xiaomi_vince" path="device/xiaomi/vince" remote="vince"/>
    <project name="device_xiaomi_msm8953-common" path="device/xiaomi/msm8953-common" remote="vince"/>

    <!--Vendor Tree-->
    <project name="vendor_xiaomi_vince" path="vendor/xiaomi/vince" remote="vince"/>
    <project name="vendor_xiaomi_msm8953-common" path="vendor/xiaomi/msm8953-common" remote="vince"/>

    <!--Kernel Tree-->
    <project name="kernel_xiaomi_msm-8953" path="kernel/xiaomi/msm8953" remote="vince"/>
</manifest>
```


## Spec Sheet

| Feature                 | Specification                     |
| :---------------------- | :-------------------------------- |
| CPU                     | Octa-core 2.0 GHz Cortex-A53      |
| Chipset                 | Qualcomm MSM8953 Snapdragon 625   |
| GPU                     | Adreno 506                        |
| Memory                  | 3/4 GB                            |
| Shipped Android Version | 7.1.2                             |
| Storage                 | 32/64 GB                          |
| MicroSD                 | Up to 256 GB                      |
| Battery                 | 4000 mAh (non-removable)          |
| Dimensions              | 158.5 x 75.4 x 8.0 mm             |
| Display                 | 2160x1080 pixels, 5.9 (~401 PPI)  |
| Rear Camera             | 12 MP, LED flash                  |
| Front Camera            | 5 MP                              |
| Release Date            | April 2017                        |

## Device Picture

![Xiaomi Redmi 5 Plus](https://i.imgur.com/2FYdLQK.jpg "Xiaomi Redmi 5 Plus")


# Cheeseburger:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
    <remote name="los" fetch="https://github.com/LineageOS/" revision="lineage-21" />
    <remote name="Muppets" fetch="https://github.com/TheMuppets/" revision="Muppets" />

    <!-- Device Tree -->
    <project name="android_device_oneplus_cheeseburger" path="device/oneplus/cheeseburger" remote="los"/>
    <project name="android_device_oneplus_msm8998-common" path="device/oneplus/msm8998-common" remote="los"/>

    <!--Kernel Tree-->
    <project name="android_kernel_oneplus_msm8998" path="kernel/oneplus/msm8998" remote="los"/>

    <!--Vendor Tree-->
    <project name="proprietary_vendor_oneplus_cheeseburger" path="vendor/oneplus/cheeseburger" remote="Muppets" revision="lineage-21"/>
    <project name="proprietary_vendor_oneplus_msm8998-common" path="vendor/oneplus/msm8998-common" remote="Muppets" revision="lineage-21"/>

    <!--Hardware Tree-->
    <project name="android_hardware_oneplus" path="hardware/oneplus" remote="los"/>
</manifest>
```

# HotDogB:

```xml
<?xml version="1.0" encoding="UTF-8"?>
<manifest>
    <remote name="los" fetch="https://github.com/LineageOS/" revision="lineage-21" />
    <remote name="Muppets" fetch="https://github.com/TheMuppets/" revision="Muppets" />

    <!-- Device Tree -->
    <project name="android_device_oneplus_hotdogb" path="device/oneplus/hotdogb" remote="los"/>
    <project name="android_device_oneplus_sm8150-common" path="device/oneplus/sm8150-common" remote="los"/>

    <!--Kernel Tree-->
    <project name="android_kernel_oneplus_sm8150" path="kernel/oneplus/sm8150" remote="los"/>

    <!--Vendor Tree-->
    <project name="proprietary_vendor_oneplus_hotdogb" path="vendor/oneplus/hotdogb" remote="Muppets" revision="lineage-21"/>
    <project name="proprietary_vendor_oneplus_sm8150-common" path="vendor/oneplus/sm8150-common" remote="Muppets" revision="lineage-21"/>

    <!--Hardware Tree-->
    <project name="android_hardware_oneplus" path="hardware/oneplus" remote="los"/>
</manifest>
```
