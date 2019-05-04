Umidigi Devices Repository
![Umidigi Devices](https://www.umidigi.com/images/others/umidigi_logo.png)
==========================
Actual Devices in this Repository:

The Umidigi S3-Pro (codenamed _"S3-Pro"_) is a flagship smartphone from Umidigi.
It was announced on 2019.

Basic   | Spec Sheet
-------:|:-------------------------
CPU     | 2.0GHz Octa-Core MT6755 (Helio P60)
GPU     | Mali-T860
Memory  | 6GB RAM
Shipped Android Version | 9.0
Storage | 128GB
Battery | 5150 mAh
Display | 6.3" 1920 x 1080 px
Rear Camera | 48MP (Sony IMX586),LED Flash, 
Front Camera | 20MP (OV)

![Umidigi Devices](https://lh6.googleusercontent.com/14LQr0O-Maf5QWqGh1rlj6gM1W8B6tj-EFe8gQrLW4ujGYTBc6aY_zp66-BAXXm0nPEpvujv1vhYdIT_P8ipArBwskxgBUBCvS-fJ2h1dhDrYVoBeL1oZ9cBpkAcmDz8qahpuRIK "Umidigi S3-Pro in black")

This branch is for building TWRP.

### Thanks to:
 * CyanogenMod team
 * Deepflex
 * Wuxianlin
 * Ferhung
 * SHVED
 * Xen0n
 * JonnyXDA
 * olegsvs
 * Visi0nary
 * andyrichardson
 * Team M.A.D

### To build: 
```
repo init -u git://github.com/

repo sync

. build/envsetup.sh


make clean && make recoveryimage
```


