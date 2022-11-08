## (Work/Update in Progress)
Github Action for Building a Custom Kernel from Source

## Important Notes
Change/Edit Clang and GCC version, and even your target Kernel Source based on what you plan on using. Clang are currently set in Android12L-Release, version clang-r383902.

Make sure to edit it here: [build](https://github.com/cd-Spidey/Action-Kernel-Builder/blob/main/build)
```
CLANG_TAR_URL="https://android.googlesource.com/platform/prebuilts/clang/host/linux-x86/+archive/refs/heads/android12L-release/clang-r383902.tar.gz"

BINUTILS_GIT="https://android.googlesource.com/platform/prebuilts/gcc/linux-x86/aarch64/aarch64-linux-android-4.9" 

BINUTILS_32_GIT="https://android.googlesource.com/platform/prebuilts/gcc/linux-x86/arm/arm-linux-androideabi-4.9"

KERNEL_SOURCE_URL="https://github.com/cd-Crypton/realme_9SE-Q3s_kernel"
```
