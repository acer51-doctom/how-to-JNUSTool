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
        2. Put the downloaded file into `[SD CARD ROOT]/wiiu/environments/aroma/plugins`
        3. Take the SD Card out of your computer (with ejecting properly of course) and put it back in your Wii U.
        4. Go into the Aroma Plugin menu (L+DPAD-DOWN+Select/Minus button)
        and you should see the `ftpiiu` plugin.
        5. Select the `ftpiiu` plugin and press A
        6. Take note of the IP Address and port (exemple: 192.168.1.110:21)
        [!NOTE]
        This isn't your public IP Address, it's your local one. Meaning, nobody can track you down with the given IP Address on your Wii U.
        7. Select `Enable ftpd` and set it to `true`
        8. Go to `Allow access to system files` and set it to `true`
        [!IMPORTANT]
        This will give us access to System Files. Do **NOT** mess things up. I am not reponsible for any damages, as said before.
        [!NOTE]
        If the Aroma method doesn't works, switch over to the [Tiramisu](https://tiramisu.foryour.cafe) method.
    
    - If on TIRAMISU:
        1. Go to the HB App Store
        2. Search `ftpiiu` <br> ![Search image of `ftpiiu`](/assets/images/tiramisu_ftpiiu_hbappstore_search.png)
        3. Tap on `FTPiiU Everwhere`
        
- JNUSTool (included in Releases OR check [this link for original work](https://github.com/Maschell/JNUSTool/releases/tag/0.3b))
- Java to run the .jar files


----------------------------------------------------------------------------

### Table of Contents

***[Section I](/assets/Section1.md)***: What is JNUSTool? <br>
***[Section II](/assets/Section2.md)***: How can I use JNUSTool? <br>
***[Section III](/assets/Section3.md)***: How do I replace dumped files with JNUSTool? <br>
Extras:
***[Section IV](/assets/Section4.md)***: Wii U Title IDs Databases (including vWii & virtual console)

Continue to [Section I...](/assets/Section1.md)

<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>
`Post-Scriptum: In memory of [Ben "bushing" Byer](https://hackmii.com/ben),
a team fail0verflow/Twiizers member.`