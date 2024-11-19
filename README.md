# Flashrom_AppImage
########################################################################
<br> Thank you for sharing this project across the internet! <br/>
<br> If you like it don't forget to give an star. <br/>
<br> By the way this is an unofficial project. <br/>
########################################################################
1ST make a backup

`sudo ./FlashRom-x86_64.AppImage -p ch341a_spi -c "W25Q64BV/W25Q64CV/W25Q64FV" -r /home/lucas/Downloads/lucas2.bin`

2ND Record the BIOS

`sudo ./FlashRom-x86_64.AppImage -p ch341a_spi -c "W25Q64BV/W25Q64CV/W25Q64FV" -w /home/lucas/Downloads/lucas.bin`

3RD Erase the BIOS

`sudo ./FlashRom-x86_64.AppImage --programmer ch341a_spi -c "W25Q64BV/W25Q64CV/W25Q64FV" -E`
<h1>Telegram Group<h1/>
<h1>https://t.me/appimagelucasmz1<h1/>
