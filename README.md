# buildroot-vex-v5

Buildroot `BR2_EXTERNAL` tree for building Linux targeting the VEX V5 Brain. This outputs bootable images for the [valenki bootloader](https://github.com/tropicaaal/valenki) (kept private at the moment).

for menuconfig:

```
make BR2_EXTERNAL=../buildroot-vex-v5 menuconfig
make savedefconfig
```

to build images:

```
make BR2_EXTERNAL=../buildroot-vex-v5 zynq_vex_v5_defconfig
make
```
