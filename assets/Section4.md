# Section IV: How do I replace dumped files with JNUSTool?

There is one main way to replace system files: via FTP or SDCafiine for apps.

There is two main ways to replace the dumped files to the SLC. (FTP)

 Click [here](#Aroma) to see the [Aroma](#Aroma) method. <br>
 Click [here](#Tiramisu) to see the [Tiramisù](#Tiramisu) method.

----------------------------------------------------------------------------

<a name="Aroma">Via Aroma:</a>
Remember the ftpiiu plugin? Well we are gonna use it.

## Wii U Side

1. Boot your Wii U. If already booted in Aroma Environment (in case of autoboot), skip to step 4.
> [!NOTE]
> The following steps are if you don't have AutoBoot directly into Aroma installed. Go to [this page if you want Aroma autoboot.](https://wiiu.hacks.guide/aroma/autobooting.html). Though, you need to have H&S autobooting.
2. Load your correct Environment (Aroma)
3. Load to the Wii U Home Menu (not vWii)
4. Press L+DOWN+SELECT on your GamePad. You will see the Plugin Menu.
5. Go to ftpiiu and press A.
6. Ensure that access to System Files is enabled.
> [!WARNING]
> After this point, do NOT touch anything else to your console. FTP is now activated and if you mess something up, I'm not responsible!
7. Take note of the IP Address shown and port.

## PC Side

1. Open your FTP Client
2. Input the IP address in `host` section and your port in the `port` section. Usually it's 21 which is default for almost everything.
3. For the login, you need to put either `anonymous` or if there's an anonymous check box, tick it and hit the connect button.
4. Once your Wii U is connected via FTP, you should see something like `storage_slc` or `slc`. Click it and your Wii U will retrieve the files to show you.
5. Navigate now to `storage_slc/title/0050010/1000400A/code` and you should have a bunch of files. We are looking for `swkbd.rpl`, for exemple to replace the Wii U Keyboard.
> [!CAUTION]
> EXTREME CAUTION, TO STEP 6 UNTIL STEP 8, YOU WILL ONLY HAVE 30 SECONDS TO 1 MINUTE TO APPLY THEM BEFORE YOUR FTP CLIENT DISCONNECTS. YOU WILL NEED TO BE **QUICK!!**
6. Quickly minimize your FTP Client and open a Finder/File Manager/Explorer window where your file that you need to replace is. For simplicity, I will go back to my exemple of replacing the keyboard.
7. Copy your file that you wanted to replace (`swkbd.rpl` in my exemple/case)
8. Go back to your FTP client and hit CTRL+V or ⌘ Command+V to paste the file you wanna replace. Reboot and done!

----------------------------------------------------------------------------

<a name="Tiramisu">Via Tiramisù:</a>
Via Tiramisu, it's gonna be a bit more complicated but very similar to the Aroma method.
> [!NOTE]
> This method can also be used if you can't do it on Aroma.

## Wii U Side

1. Boot your Wii U in the Tiramisù environment.
2. Go into Mii Maker for the Homebrew Launcher.
3. Open FTPiiU_Everywhere
> [!NOTE]
> It is very important to use FTPiiU_Everywhere! It'll allow us access to system files!
4. Take note of the IP Address and port.
> [!Warning]
> Do not touch your Wii U! You will see a bunch of text appear but that's **NORMAL!!**


## PC Side

1. Open your preferred FTP client.
2. Connect to the IP Address and Port using the anonymous mode. You will see a bunch of text on your TV Screen but once again it's normal.
3. Navigate now to `storage_slc/title/0050010/1000400A/code` and you should see a bunch of files.
> [!CAUTION]
> Caution! Be extremely careful! You will only have 30 seconds to 1 minute to go through step 4 to 6.
4. **MINIMIZE** your ftp client and go to the folder where JNUSTool is located in File Manager/Finder/Explorer
> [!Tip]
> There might be subfolders before you can actually get the file. Go through the subfolders and THEN copy the file that is desired.
5. Copy (CTRL+C or ⌘ Command+C) your desired file
6. Go back to your FTP Client and paste (CTRL+V or ⌘ Command+V) the file that you wanna replace or is missing.
7. Click the Home button on your gamepad and reboot the console.

----------------------------------------------------------------------------

And there you have it! You've **sucessfully** changed a file in your SLC! Have fun with your Wii U!
If you have any issues *(even tho i'm not responsible for any damage)* I'll try my best to help.

Goodluck!