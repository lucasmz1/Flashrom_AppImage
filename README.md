# Flashrom_AppImage
Unoffical
1ST make a backup

`sudo ./FlashRom-x86_64.AppImage -p ch341a_spi -c "W25Q64BV/W25Q64CV/W25Q64FV" -r /home/lucas/Downloads/lucas2.bin`

2ND Record the BIOS

`sudo ./FlashRom-x86_64.AppImage -p ch341a_spi -c "W25Q64BV/W25Q64CV/W25Q64FV" -w /home/lucas/Downloads/lucas.bin`

3RD Erase the BIOS

`sudo ./FlashRom-x86_64.AppImage --programmer ch341a_spi -c "W25Q64BV/W25Q64CV/W25Q64FV" -E`
