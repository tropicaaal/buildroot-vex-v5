# buildroot-vex-v5

Buildroot `BR2_EXTERNAL` tree for building Linux targeting the VEX V5 Brain. This outputs bootable images for the [vanda](https://github.com/tropicaaal/vanda) bootloader (which is kept private at the moment due to competition integrity concerns, so booting is left as an exercise to the reader).

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
