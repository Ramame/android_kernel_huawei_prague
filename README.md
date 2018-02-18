# Huawei P8 Lite 2017 PRA-LX1 Kernel Source

* This is the kernel source for PRA-LXX aka "Prague" devices, if you want to compile your image just follow my own steps;

## Compatibility

* Android 7.x Nougat = YES
* Android 8.x Oreo = YES

## Compile Your Own Kernel

* Clone your favorite version by

**git clone https://github.com/hak86/android_kernel_huawei_prague -b 8.x kernel/huawei/prague**

* Run the following command:

**cd kernel/huawei/prague
./build.sh**

* Where is Image file?
go to **out/arch/arm64/boot/** and inside that folder will find an image called **Image**..flash it..enjoy..
