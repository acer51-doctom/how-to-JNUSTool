# Section III: How can I use JNUSTool?

The use of JNUSTool is very simple.

First of all, you're gonna need the TitleID of what you wanna download. <br>
Exemple: American home menu, European Mii Maker, you get it. <br> <br> To get the TitleID you need, refer to (https://wiiubrew.org/wiki/Title_database)[https://wiiubrew.org/wiki/Title_database].

Tho, there's still some SLC files you might need... The Gamepad Keyboard for exemple, which is in the SLC.

There are some OS version you need to know for the SLC.

- OSv0 (cafe2wii, loads the vWii menu)
- OSv1 (loads enhanced vWii titles downloaded from eShop)
- OSv9 (Launch-day (wii u internal) OS)
- OSv10 (The normal OS when you turn on your wii u)
- OSv255 (Updater)

To download one of the files that is corresponding to the correct OS that you need (OSv10 for exemple), <br>
You will need to use the Terminal (or CMD on windows (i'm on mac don't judge))

1. Put the files of JNUSTool inside of a folder on, for exemple, your desktop
2. Double click JNUSTool.jar
You should see a CommonKey error. This is normal.
3. Get a valid OTP.bin if you didn't already dump it.
4. Get the CommonKey from using either:
    - A Hex Editor (more risky since you can accidentally modify the OTP.bin)
        1. Open your favorite Hex Editor. I will be using Hex Fiend but it shouldd be the same for everyone else.
        2. Drag and drop or open the OTP.bin file
        ![Draging and dropping the OTP.bin inside of the hex editor I'm using](/assets/images/drag_and_drop_otp.gif)
        3. Then go to the 0xE0 (which is in my hex editor maked with "0E0") and copy the first 32 bytes
        > WARNING! :warning: Your hex editor might select two bytes by two bytes! Be carefully with it! AND NO THE SPACES DO NOT COUNT AS A BYTE!!!!
        4. Copy the string inside of a notepad window
    - The CommonKey extractor
        1. Open the `extractor.exe`
        2. Select your OTP.bin 
        3. Open it and hit the copy button next to it. 
        4. Copy the string inside of a notepad window
        ![no](/assets/images/commonkey_extractor_section3.gif)