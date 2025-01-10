# Section III: How can I use JNUSTool?

The use of JNUSTool is very simple.

First of all, you're gonna need the TitleID of what you wanna download. <br>
Exemple: American home menu, European Mii Maker, you get it. <br> <br> To get the TitleID you need, refer to [the Wii U Title IDs database](https://wiiubrew.org/wiki/Title_database).

Tho, there's still some SLC files you might need... The Gamepad Keyboard for exemple, which is in the SLC.

There are some OS version you need to know for the SLC.

| OS Version | What does it do OR what is it? | TitleID |
| ---| --- | --- |
| OSvO - cafe2wii | Loads vWii Menu | 0005001010004000 |
| Osv1 | Loads "Enhanced" vWii titles downloaded from the eShop | 0005001010004001 |
| OSv9 - Launch-Day | Launches Wii U's internal OS before CafeOS | 005001010004009 |
| OSv10 - CafeOS | Your normal Wii U interface once fully booted | 000500101000400A |
| OSv255 - Updater | What the Wii U uses to update | 00050010100040FF |

You mainly will need OSv10. The other ones are for bestowing knowledge.

> [!NOTE]
> The OSv10 (which is what you need) contains some key files like the Wii U Keyboard or even "drivers" to the camera. If your SLC is corrupted and you lost everything, buy another Wii U. I can't help with that even if I wanted to.

To download one of the files that is corresponding to the correct OS that you need (OSv10 for exemple), you will need to use either:

- The Terminal (Mac and Linux)
- Command Prompt (Windows)

To launch JNUSTool. Anyways, you're gonna need to do the following steps to geet your CommonKey for JNUSTool.

1. Put the files of JNUSTool inside of a folder on, for exemple, your desktop
2. Double click JNUSTool.jar
You should see a CommonKey error. This is normal.
3. Get a valid OTP.bin if you didn't already dump it.
4. Get the CommonKey from using either:
    - A Hex Editor (more risky since you can accidentally modify the OTP.bin)
        1. Open your favorite Hex Editor. I will be using Hex Fiend but it shouldd be the same for everyone else.
        2. Drag and drop or open the OTP.bin file
        ![Draging and dropping the OTP.bin inside of the hex editor I'm using](/assets/images/drag_and_drop_otp.gif)
        3. Then go to the 0xE0 (which is in my case, in my hex editor, written by "0E0" in the left side bar.) and copy the first 32 bytes
        > WARNING! :warning: Your hex editor might select two bytes by two bytes! Be carefully with it! AND NO THE SPACES DO NOT COUNT AS A BYTE!!!!
        4. Copy the string inside of a notepad window for ease instead of keeping it in your copy and paste history.
    - The CommonKey extractor (Note that it works with Windows only since it's a .exe. You can use Wine [^1] or CrossOver[^2] to use the software. I didn't try it out but you can.)
        1. Open the `extractor.exe`
        2. Select your OTP.bin 
        3. Open it and hit the copy button next to it. 
        4. Copy the string inside of a notepad window
        ![no](/assets/images/commonkey_extractor_section3.gif)

5. After that, go into the `config` file of the JNUSTool folder
6. Replace the `[COMMONKEY]` with your actual commonkey (please DO delete the brackets)
6. Go into Terminal or CMD (depending if you're on Windows, Linux or Mac)
7. Go to the directory inside of Terminal/CMD
8. Type the following `java -jar JNUSTool.jar [TitleID you need]` (refer to [the Wii U Title IDs database](https://wiiubrew.org/wiki/Title_database) previously mentioned)
9. Hit the Enter/Return key on your keyboard
10. A window should pop-up and some text should also get into the terminal. If you used OSv10, you should get this (or something similar). ![nuh uh no alts](/assets/images/jnustool_osv10.png) 
11. Click the small arrow next to the check box of `code` then you should get a whole bunch of .rpl, some .elf, .rpx, .txt and .img files. <br> You may recognize .elf and .rpx files in the list of files I listed above. And as you guessed, these files are the same as you may use or have used before! (In terms of Homebrew)
12. Tick the boxes of the files you may need and hit the Download button.
13. Go to the JNUStool folder where you have previously put JNUSTool.jar and there should be a new folder that has appeared with the new files.

Proceed to [the final Section, Section IV...](/assets/Section4.md)

[^1]: Free to use. Check it out here: https://gitlab.winehq.org/wine/wine/-/wikis/Download
[^2]: Free trial of 14 days. Costs 75$. Check it out here: https://www.codeweavers.com/crossover/ but I don't think you wanna pay 75$ just for a github tutorial.
