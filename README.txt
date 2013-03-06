export ARCH=arm
export PATH=~/alps/prebuilt/linux-x86/toolchain/arm-linux-androideabi-4.4.x/bin:$PATH

Build command:

kernel
======
cd kernel
cp mediatek-configs .config
TARGET_PRODUCT=s8073 MTK_ROOT_CUSTOM=../mediatek/custom make
