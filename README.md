# TWRP for the Motorola E13

I made this by modifying the TWRP that Hovatek's online builder gave me, so I don't have the source code(for now). I plan to Recompile this on my PC later.

## Flashing
- Unlock bootloader using [CVE-2022-38694](https://github.com/MotorolaE13/CVE-2022-38694_unlock_bootloader)
- Flash from fastboot(not fastbootd) using ```fastboot flash vendor_boot_a vendor_boot_twrp.img```

   I guess you can also flash it from fastbootd but i haven't tested that.
