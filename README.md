# An Open-Source Implementation of the OpenGL Specification, PowerVR (VisionFive2)

## Deprecated

This repository is deprecated in favor of the PowerVR DDK 11.9 wrapper [mesa-pvr-ddk119](https://github.com/cwt-vf2/mesa-pvr-ddk119).

Please replace this package with the latest `mesa` package from Arch Linux RISC-V:

```
$ sudo pacman -S mesa
resolving dependencies...
looking for conflicting packages...
:: mesa-1:24.3.3-1 and mesa-pvr-vf2-22.1.7-1 are in conflict. Remove mesa-pvr-vf2? [y/N] y

Packages (3) mesa-pvr-vf2-22.1.7-1 [removal]  spirv-tools-2024.4.rc1-1  mesa-1:24.3.3-1

Total Download Size:   16.32 MiB
Total Installed Size:  79.37 MiB
Net Upgrade Size:      59.15 MiB
```

And then download and install the `mesa-pvr-ddk119`:

```
$ wget https://github.com/cwt-vf2/mesa-pvr-ddk119/releases/download/22.1.7-1/mesa-pvr-ddk119-22.1.7-1-riscv64.pkg.tar.zst
$ sudo pacman -U mesa-pvr-ddk119-22.1.7-1-riscv64.pkg.tar.zst
```
