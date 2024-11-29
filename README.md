# How-To-JNUSTool
How-to: Use JNUSTool

This guide contains everything you need and explains how to use JNUSTool (i'm late to this i swear)

**:warning: BEFORE HAND REQUIREMENTS!! :warning:**

> [!IMPORTANT]
The methods used in this guide will give you access to System Files. Do NOT mess something up. I'm not responsible for anything, at your own risk!

- Aroma **OR** Tiramisu CFW Environment
- An FTP Client (PC Side)
- A valid `OTP.bin`
- A hex editor
- FTPiiU
    - If on AROMA:
        1. Go to the Releases OR [the Aroma page](https://aroma.foryour.cafe)
            - If on the Aroma page, check every boxes and go down until you see the `Additional Plugins and Modules` and CHECK, ONLY CHECK THE FTPIIU PLUGIN!! Then Download. ![Image of the Additional Plugins and Modules section and FTPiiU plugin selected.](/assets/images/aroma_ftpiiu_plugin.png)
        2. Put the downloaded file into `[SD CARD ROOT]/wiiu/environments/aroma/plugins` ![FTPiiU placement on the SD Card](/assets/images/ftpiiu_placement_aroma.png)
        3. Take the SD Card out of your computer (with ejecting properly of course) and put it back in your Wii U.
        4. Go into the Aroma Plugin menu (L+DPAD-DOWN+Select/Minus button)
        and you should see the `ftpiiu` plugin.
        5. Select the `ftpiiu` plugin and press A
        6. Take note of the IP Address and port (exemple: 192.168.1.110:21)
        > Note:
        This isn't your public IP Address, it's your local one. Meaning, nobody can track you down with the given IP Address on your Wii U.
        7. Select `Enable ftpd` and set it to `true`
        8. Go to `Allow access to system files` and set it to `true`
        > :warning: IMPORTANT :warning:
        This will give us access to System Files. Do **NOT** mess things up. I am not reponsible for any damages, as said before.
        > Note:
        If the Aroma method doesn't works, switch over to the [Tiramisu](https://tiramisu.foryour.cafe) method.
    
    - If on TIRAMISU:
        1. Go to the HB App Store
        2. Search `ftpiiu` ![Search image of `ftpiiu`](/assets/images/tiramisu_ftpiiu_hbappstore_search.png)
        3. Tap on `FTPiiU Everwhere` ![FTPiiU-Everywhere page to download](/assets/images/download_page_ftpiiu_everywhere.png)
        4. Press A to download
        5. Reboot to Tiramisu if you already weren't in it
        6. Go through the pages until you find FTPiiU-Everywhere
        7. Launch FTPiiU-Everywhere and note the IP Address and port
        8. Exit via the HomeButton then wait..
        
- JNUSTool (included in Releases OR check [this link for original work](https://github.com/Maschell/JNUSTool/releases/tag/0.3b))
- Java to run the .jar files


----------------------------------------------------------------------------

A lot of this guide is WIP (=Work In Progress) and will be completed soon!!!!

Every file needed will be in the Releases section (excluding Tiramisu or Aroma since I assume you already have cfw...)


----------------------------------------------------------------------------

### Table of Contents

***[Section I](/assets/Section1.md)***: What is JNUSTool? <br>
***[Section II](/assets/Section2.md)***: How can I use JNUSTool? <br>
***[Section III](/assets/Section3.md)***: How do I replace dumped files with JNUSTool? <br> <br>
Extras: <br> <br>
***[Section IV](/assets/Section4.md)***: SLC file system + title ids

Continue to [Section I...](/assets/Section1.md)

Special thanks to the creators of:

- JNUSTool
- FTPiiU Plugin and FTPiiU Everywhere
- Java
- Tiramisu and Aroma

If I missed special thanks to someone, contact me on Discord
`its_a_me_.arthur`

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
`Post-Scriptum: In memory of [Ben "bushing" Byer](https://hackmii.com/ben),
a team fail0verflow/Twiizers member.`