## kernel - xiaomi davinci
https://github.com/dencel007/android_kernel_xiaomi_davinci

#### branches :

- 
- 

#### build commands :

    make clean
    make mrproper
    export ARCH=arm64 /
    export CROSS_COMPILE=<toolchain path>/bin/<toolchain prefix> /
    mkdir -p out /
    make O=out <your_defconfig_filename_here> /
    make O=out -j$(nproc --all)

**credits and thanks to committers**