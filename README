.

TODO: Use upstream meta-rockchip and add support to your machine
	https://git.yoctoproject.org/meta-rockchip/

TODO: use poky/README upstream

TODO: add your custom layer for configurations


~/yocto-rk3562 $ git clone --recursive
~/yocto-rk3562 $ source poky/oe-init-build-env
~/yocto-rk3562 $ bitbake core-image-minimal

Uboot defconfig:
meta-rockchip -> $ ack rk3562_defconfig

===============================================================================
Ubuntu@yocto-rk3562 $ bitbake core-image-minimal
ERROR: User namespaces are not usable by BitBake, possibly due to AppArmor.
See https://discourse.ubuntu.com/t/ubuntu-24-04-lts-noble-numbat-release-notes/39890#unprivileged-user-namespace-restrictions for more information.

Summary: There was 1 ERROR message, returning a non-zero exit code.
Ubuntu@yocto-rk3562 $ sudo -s
root@smalinux:/src/yocto-rk3562# sudo echo 0 > /proc/sys/kernel/apparmor_restrict_unprivileged_userns
root@smalinux:/src/yocto-rk3562#

===============================================================================
