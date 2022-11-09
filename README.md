## (Work/Update in Progress)
Github Action for Building a Custom Kernel from Source

## Important Notes
- Change Clang and GCC version, and even your target Kernel Source based on what you plan on using.
- Clang are currently set in android11-release, version clang-r383902.
- To change, open `build` file, and edit everything you wish to change.
- Also, do not forget to edit and change the name_defconfig part.

## Releases Note (Please Read)
- Instead of automatically put the compiled kernel (Image, Image-dtb, or whatever the name was) inside AnyKernel3.zip, I made 2-n-1 release.
- AnyKernel3.zip (without kernel inside), and myKernel.zip (with kernel inside).
- You need to extract myKernel.zip, copy/move the kernel inside.
- Extract AnyKernel3.zip and place the kernel from myKernel.zip inside the AnyKernel folder and compress it, then you can flash it now.
- I made it like this as kernel comes with different names sometimes, and for others who need kernel with dtb—their Custom Recovery Compiling.
