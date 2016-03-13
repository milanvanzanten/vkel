
# vkel - Changelog

## 2.0.2 - Revision 5, 2016/03/12
- Updated support for Vulkan 1.0.6

## 2.0.1 - Revision 4, 2016/03/06
- Updated support for Vulkan 1.0.5

## 2.0.0 - Revision 3, 2016/02/26
- Rewrote vkel_gen.py, now it parses and directly adds vulkan.h and vk_platform.h into vkel.h,
along with moving the appropriate copyrights to the top of vkel.h.
- Fixed/added better differentiation for instance and device related calls.
- Removed the need for having the vukan.h and vk_platform.h headers.
- Updated support for Vulkan 1.0.4

## 1.1.0 - Revision 2, 2016/02/24
- Created a Python script for automatically generating all the extensions and their functions. (Developed and tested using Python 3.5.1)
- Added cross-platform support, for loading libraries and getting the function addresses.
- Fixed so platform specific functions defaults to NULL
- Added missing include for dlfcn (used on non-Window OS')

## 1.0.0 - Revision 1, 2016/02/23
- Implemented the basic version supporting a few (manually written) dynamically loaded functions.