# Wii U Menu Themes
![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/81m1tr1/WiiU-Menu-Themes/total?style=plastic&logo=wiiu&logoColor=%230000FF&logoSize=auto&color=black) ![GitHub Release](https://img.shields.io/github/v/release/81m1tr1/WiiU-Menu-Themes?sort=semver&display_name=release&style=plastic&label=Latest&labelColor=red)

---
Custom Wii U Themes which are tested on the Aroma custom Frimware on WiiU
## What you need before usage
1. A modded WiiU with the [Aroma](https://aroma.foryour.cafe/) Enviorment
2. SDCard
3. Sdcafiine
4. FTPIIU Plugin
---
**ftp client:**
- Windows: https://winscp.net/eng/download.php
- Mac: https://cyberduck.io/download/
---
## Installation
### Dumping Files you need
> If you already have Men.pack, Men2.pack and cafe_barista_men.bfsar files you may skip this Step
1. Turn on your console without any custom theme running on SDCafiine, this will cause issues when getting the files we need
2. Press L + DPAD Down + Select and search for FTPiiU
3. Press Settings and enable everything
4. On your computer open the ftp client
> The following steps are for Windows users, if you dont use windows try doing something similar to what  im doing below
5. It will ask for your Console IP and Port Number
- ```Example: 192.168.0.67  // Port: 21```
6. It will ask for a user and a password leave it in blank, just accept
7. Now navigate to
```storage_mlc/sys/title/00050010/10040X00/content/Common/Package```
- USA: 10040100
- EUR: 10040200
- JPN: 10040000
8. Select Men.pack and Men2.pack then press Download
- **Always Backup Files!!!**
9. Now we will do the same but for the bfsar file
10. Go back and then navigate into Sound > Men 
11. Download cafe_barista_men.bfsar
---
### Patching Files
1. Open [Rom Patcher JS](https://www.marcrobledo.com/RomPatcher.js/) on your browser
2. for the ROM file get your original (Men.pack / Men2.pack / cafe_barista_men.bfsar) file
> For this example we will be using Men.pack
3. For the Patch File select the .ips, .bps, .ups, .ppf, .aps, .rup file you got from downloading the theme that matches the name of the ROM file
4. Press Apply patch
5. rename of the file to the original name of the file 
> *Now repeat with the other files*
---
### Building Files
- You Need SDcafiine
- ThemeName is free to Choose!
- The Filestructure should look like this:

For Visuals:
>```sd:/wiiu/sdcafiine/[TITLEID]/[ThemeName]/content/Common/Package/Men.pack, Men2.pack```

For Audio:
> ```sd:/wiiu/sdcafiine/[TITLEID]/[ThemeName]/content/Common/Sound/Men/cafe_barista_men.bfsar```

TITLEID:
> - USA:0005001010040100
> - EUR:0005001010040200
> - JPN:0005001010040000

## Themes Collection
| Name | Type | WWP [^1] | Custom Music | Release |
|:-|:-|:-|:-|:-|
| Kurumi | Static | Yes | Yes | v.1.0.0 |
| Nsmbu | Animation | Yes | Yes | v.1.0.0 |
| Hatsune Miku | Animation | Yes | Yes | v.2.0.0 |
| Mario Maker | Animation | No | Yes | v.3.0.0 |

[^1]: WPP:  Wara Wara plaza, where the Mii's run around.
## Other Themes or need Help?
[Discord Link](https://discord.gg/Q52AUxX6jz)
