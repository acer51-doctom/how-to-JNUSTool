# Section II: What is an SLC? (and other chips of the motherboard)

First of all, let's take the previous exmple to explain what is this SLC thing and other...

The SLC is gonna be **important** files critical to the proper function of the system like CafeOS.

> [!TIP]
The Wii U has 2 chips. The SLC (containing the SLCCMPT which we will look at later and other stuff) and the MLC (which is stocked your games for exemple and also the Home Menu)

But for exemple, the SLC will contain, your **Wii U keyboard!** but also critical things like the **second stage bootloader (boot1); the core Operating Systems (IOSU and CafeOS).**

It also has the tickets to eShop titles and System apps and some config files.

The SLCCMPT which is a different partition of the SLC (but still the same chip in hardware) will control the vWii or more commonly named, the Wii Mode. If you wanna ruin absolutely everything your vWii then just delete everything in the SLCCMPT and you're done (this is sarcasm. do not do it.)

The MLC (also commonly named, eMMC) is gonna be all the user stuff like Games, save files, accounts but also holds system apps like **Settings** and other stuff. It can be 8GB or 32GB but, everyone knows that. Right?

The SEEPROM is pretty different tho. It contains the boot1 version aswell as the USB Key, Disc Drive key, ram config and some other things.

Then, there is the OTP partition in the Latte chip containing a bunch of keys (SLC, MLC, SEEPROM, CommonKey (which is what you need for JNUSTool btw) and all the other stuff I'm talking about.) Deleting the OTP would be devastating since your Wii U basically can't unlock any "doors" to access the System so you end up with a brick. That can't be recovered, of course. Where's the fun without that?

Then, there is the Starbuck in the Latte chip also. It contains the boot0 sector which loads boot1.

There's also the Espresso chip which also has it's own bootrom.

Then you have any components like the SMC, Disc Drive, Wireless modules, ect ect... they also have their own firmware installed.

> [!IMPORTANT]
Only some certain things can be dumped via the payload called `nanddumper` which includes:

- The MLC
- The SLC
- The SLCCMPT
- The SEEPROM
- The OTP

Nothing else can be dumped without having special tools (desoldering the chips and resoldering them). Or is just impossible to dump.

Proceed to [Section III...](/assets/Section3.md)