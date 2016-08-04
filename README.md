# R-Kernel
Kernel for Huawei P6-U06 (Omni RE.D)
Development of angels-group - https://github.com/hwmt1-u06/android_kernel_huawei_hwmt1-u06 kernel. Improved Razziell me.Sorry for my English.
   
   How to Build:
   cd Kernel
   make ARCH=arm hwp6_u06_defconfig
   make ARCH=arm zImage -j3 # -j 3 - the number of threads +1
