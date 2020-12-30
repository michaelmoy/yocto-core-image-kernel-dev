# yocto-core-image-kernel-dev
A Linux CLI build, setup for Development

This build is Linux 5.8 CLI only with Dev tools that allow for cloning git repos and building code.

Build command:
bitbake core-image-kernel-dev

Build Configuration:
BB_VERSION           = "1.48.0"
BUILD_SYS            = "x86_64-linux"
NATIVELSBSTRING      = "universal"
TARGET_SYS           = "x86_64-poky-linux"
MACHINE              = "genericx86-64"
DISTRO               = "poky"
DISTRO_VERSION       = "3.2"
TUNE_FEATURES        = "m64 core2"
TARGET_FPU           = ""
meta
meta-poky
meta-yocto-bsp       = "gatesgarth-next:456e2b42404e46b352c6ac0d73fe9fcd594e5001"
meta-oe              = "gatesgarth-next:ec9065c822c0befa33425561ed646c1e734296fa"

