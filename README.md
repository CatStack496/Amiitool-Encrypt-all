# Amiitool-Encrypt-all
This is just a batch file I made to encrypt all the Amiibo bins I [TOTALLY LEGALLY AQUIRED], in a popular folder layout that goes by game series.

This will require having a key_retail.bin (WHICH I WILL *NOT* BE TELLIN GYOU WHERE TO GET IT), a copy of Amiitool, the specified amiibo folder layout( which is *totally* not something you can download off the internet in the very same folder layout), the empty version of the amiibo folder with the same layout called "amiiboEncrypted", and this batch file to iterate over all 840 decrypted amiibo files.

Here was my file file tree, minus the 840 amiibo bin filenames to spare you the excessive scrolling
```
.amiitool-win64
|   amiitool.exe *REQUIRED... because its the tool used to make this happen*
|   apache-2.0.txt
|   encrypt_all_amiibos.bat *REQUIRED Literally the batch script this repo is for*
|   key_retail.bin *REQUIRED*
|   LICENSE-amiitool
|   LiCENSE-mbedtls
|   
+---amiibo *REQUIRED with all 840 amiibos inside*
|  +---8-bit Mario
|  |       not shown
|  +---Animal Crossing
|  |       not shown
|  +---BoxBoy!
|  |       not shown
|  +---Chibi-Robo!
|  |       not shown
|  +---Diablo
|  |       not shown
|  +---Fire Emblem
|  |       not shown
|  +---Kirby
|  |       not shown
|  +---Legend Of Zelda
|  |       not shown
|  +---Mario Sports Superstars
|  |       not shown
|  +---Mega Man
|  |       not shown
|  +---Metroid
|  |       not shown
|  +---Monster Hunter
|  |       not shown
|  +---Monster Hunter Rise
|  |       not shown
|  +---Others
|  |       not shown
|  +---Pikmin
|  |       not shown
|  +---Pokemon
|  |       not shown
|  +---Power Pros
|  |       not shown
|  +---Shovel Knight
|  |       not shown
|  +---Skylanders
|  |       not shown
|  +---Splatoon
|  |       not shown
|  +---Super Mario Bros_
|  |       not shown
|  +---Super Nintendo World
|  |       not shown
|  +---Super Smash Bros_
|  |       not shown
|  +---Yoshi's Woolly World
|  |       not shown     
|  \---Yu-Gi-Oh!
|          not shown
|           
\---amiiboEncrypted *REQUIRED, preferably all subfolders empty*
    +---8-bit Mario
    |       not shown
    +---Animal Crossing
    |       not shown
    +---BoxBoy!
    |       not shown
    +---Chibi-Robo!
    |       not shown
    +---Diablo
    |       not shown
    +---Fire Emblem
    |       not shown
    +---Kirby
    |       not shown
    +---Legend Of Zelda
    |       not shown
    +---Mario Sports Superstars
    |       not shown
    +---Mega Man
    |       not shown
    +---Metroid
    |       not shown
    +---Monster Hunter
    |       not shown
    +---Monster Hunter Rise
    |       not shown
    +---Others
    |       not shown
    +---Pikmin
    |       not shown
    +---Pokemon
    |       not shown
    +---Power Pros
    |       not shown
    +---Shovel Knight
    |       not shown
    +---Skylanders
    |       not shown
    +---Splatoon
    |       not shown
    +---Super Mario Bros_
    |       not shown
    +---Super Nintendo World
    |       not shown
    +---Super Smash Bros_
    |       not shown
    +---Yoshi's Woolly World
    |       not shown     
    \---Yu-Gi-Oh!
            not shown
```

To run the batch file correctly, have your folders set up like the one shows, and run it in the main folder where amiitool resides.

HUZZAH! now you \*probaby have a folder of decrypted amiibo bins!
