# OpenCL and Vulkan on amdgpu for Arch

This package allows the usage of AMD's proprietary user-space OpenCL and Vulkan drivers along with the free amdgpu stack. This includes Linux 4.10 and newer, libdrm (requires patching as of 2.4.74) and Mesa drivers.

## Hardware support

This *should* work with all amdgpu-enabled GCN GPUs.

Currently tested with Kernel 4.10-RC2 on Hawaii and Fiji. Blender Cycles and Luxmark seem to work without any problems. The Vulkan drivers is able to run Doom 2016.

## What this is not

You are not getting faster OpenGL rendering or unicorns.

If you are looking for the full amdgpu-pro stack, including proprietary OpenGL and Vulkan implementations, move over to the [aur](https://aur.archlinux.org/pkgbase/amdgpu-pro-installer/).

Expect maintainance of this package to be dropped when there is free OpenCL and Vulkan support on top of the [ROC](https://radeonopencompute.github.io/) stack.
