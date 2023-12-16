TWRP device tree for Xiaomi Redmi 12C (earth)
======================================
The Redmi 12C is a budget range smartphone from Redmi, Released 2022, December 31

======================================
Note: This is a forked tree, All credits for Everything to YZBruh.
======================================

## Device specifications

| Basic                   | Spec Sheet                                                  |
| -----------------------:|:----------------------------------------------------------- |
| CPU                     | Octa-core (2x2.0 GHz Cortex-A75 & 6x1.8 GHz Cortex-A55)     |
| Chipset                 | MediaTek Helio G88 (MT6768 12 nm)                           |
| GPU                     | Mali-G52 MC2                                                |
| Memory                  | 4GB/6GB RAM                                                 |
| Shipped Android version | 10.0 (Go edition)                                           |
| SIM                     | Dual SIM (Nano-SIM, dual stand-by)                          |
| Storage                 | 64/128 GB                                                   |
| MicroSD                 | microSDXC, up to 128 GB                                     |
| Battery                 | Non-removable Li-Po 5000 mAh battery                        |
| Dimensions              | 168.8 x 76.4 x 8.8 mm (6.65 x 3.01 x 0.35 in)               |
| Display                 | 6.71 inches, 106.5 cm2 (~82.6% screen-to-body ratio)        |
| Sensors                 | Accelerometer, Gyro, Proximity, Compass                     |
| Features                | Fingerprint (rear-mounted), accelerometer                   |

| What's Working?                      | What's not Working?        |
| ------------------------------------:|:---------------------------|
| • Touch                              | • Decryption               |
| • MTP                                |                            |
| • ADB                                |                            |
| • Flashlight                         |                            |
| • Detect Dynamic Partitions          |                            |
| • Flashing a zip                     |                            |

## Device picture

![Redmi 12C](https://fdn2.gsmarena.com/vv/pics/xiaomi/xiaomi-redmi-12c-1.jpg "Redmi 12C")

## Build instruction

```shell
. build/envsetup.sh
lunch omni_A7S
mka recoveryimage -j $(($(nproc) + 1))
```

## Copyright

```text
    # Copyright (C) 2023 The Android Open Source Project
    # Copyright (C) 2023 TeamWin Recovery Project

    # Licensed under the Apache License, Version 2.0 (the "License");
    # you may not use this file except in compliance with the License.
    # You may obtain a copy of the License at
    #
    # http://www.apache.org/licenses/LICENSE-2.0
    #
    # Unless required by applicable law or agreed to in writing, software
    # distributed under the License is distributed on an "AS IS" BASIS,
    # WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    # See the License for the specific language governing permissions and
