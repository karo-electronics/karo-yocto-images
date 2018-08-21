# Sample images created with Yocto

An image is, for the most part, specific to the machine set in the environment
setup. Each image build creates a U-Boot binary, a Linux kernel image and a
device tree blob (DTB). These files were created for different machine types,
baseboards and kernel versions.

- Manifest
    - [Repository](https://github.com/karo-electronics/karo-bsp)
    - URL: `https://github.com/karo-electronics/karo-bsp/blob/rocko/default.xml`
    - Branch: `rocko`
    - Commit-ID (short): `a90d585`


- Project Recipes
    - [Repository](https://github.com/karo-electronics/meta-karo)
    - URL:  `https://github.com/karo-electronics/meta-karo`
    - Branch: `rocko`
    - Commit-ID (short): `5982050`

- Linux
    - URL:  `git://git.kernel.org/pub/scm/linux/kernel/git/stable/linux-stable.git`
    - Branch: `linux-4.14.y`
    - Tag name: `4.14.24`

    uImage Linux kernel images were created with the default settings      
    zImage Linux kernel images were created with appended KERNEL-FEATURE "debian"

- U-Boot
    - [Repository](https://github.com/karo-electronics/karo-tx-uboot)
    - URL:  `https://github.com/karo-electronics/karo-tx-uboot`
    - Branch: `master`
    - Tag name: `KARO-TX6-2018-01-08`

---
[Ka-Ro electronics GmbH](http://www.karo-electronics.de)

Contact support: support@karo-electronics.de
