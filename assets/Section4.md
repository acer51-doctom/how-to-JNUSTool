# Section IV: How do I replace dumped files with JNUSTool?

There is one main way to replace system files: via FTP or SDCafiine for apps.

There is two main ways to replace the dumped files to the SLC. (FTP)

 Click here to see via [Aroma](#Aroma)!


<a name="Aroma"></a>
Via Aroma:
Remember the ftpiiu plugin? Well we are gonna use it.

## Wii U Side

1. Boot your Wii U. If already booted in Aroma Environment (in case of autoboot), skip to step 4.
> [!NOTE]
> The following steps are if you don't have AutoBoot installed. Go to [this page if you want Aroma autoboot.](https://wiiu.hacks.guide/aroma/autobooting.html)
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
5. Navigate now to