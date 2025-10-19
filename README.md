# m4 hardware
Build your own M4 board

Once the M4 board is build, you should flash the bootloader onto the STM32F407 chip, using ie. ST-link on the "JTAG" header.
I also recommend to write protect the first two sectors containing the bootloader.
Afterwards copy M4FIRM.BIN and ESPFIRM.BIN to the root of a FAT32 formatted microSD card - insert it to the M4 and powercycle it.

/Duke
