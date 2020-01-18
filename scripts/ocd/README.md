mks_robin_mini_bootloader.bin is a MKS robin boards bootloader, but this one in particular is specific for Robin mini boards.
To use it you should name you .bin file as robin_mini.bin and place it into root of a SD card.
Bootloader is initialize some perephireals (SDIO, FSMC, DMA2) and set VTOR at 0x08007000.