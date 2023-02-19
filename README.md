## (Work/Update in Progress)
Github Action for Building a Custom Kernel from Source

## Important Notes
- Change Clang and GCC version, and even your target Kernel Source based on what you plan on using.
- Clang are currently set in android11-release, version clang-r383902.
- To change, open `build` file, and edit everything you wish to change.
- Also, do not forget to edit and change the name_defconfig part.

## Releases Note (Please Read)
- All built kernel will be in a folder and upload as zip.
- Download and Extract the .zip, and look for kernel inside.
- You should be able to find Image.gz, Image, Image.gz-dtb or whatever it is.
- Pick one that you actually need.
