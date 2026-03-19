In this tutorial, i'll explain in detail how to fully set up your Ryujinx emulator.

If you came from the [Ryujinx Installer Tool](https://github.com/rice-krispy2/ACTH-Installer) you can skip to the ["setup save" section of this readme](https://github.com/President00007/Ryujinx-setup---complete-tutorial-for-Animal-Crossing-New-Horizons/blob/main/README.md#moving-your-animal-crossing-new-horizons-save-from-a-yuzu-based-emulator)

I AM NOT AFFILIATED WITH NINTENDO IN ANY WAY, NOR I ENVY PIRACY. THIS IS A TUTORIAL JUST TO HELP WHO DOESN'T KNOW HOW TO SETUP THIS EMULATOR

# Installing the emulator program
- The first thing you need is, of course, the emulator. Be sure to go into [the official Ryujinx site](https://github.com/Ryubing) and select the red "canary" option as in this image.

![canary](https://github.com/user-attachments/assets/39ad3fce-fd39-4c24-85fa-09b94dc0ed74)

You should be able to find and download a file called "ryujinx-canary-VERSION-OPERATINGSYSTEM.zip" (as of writing the latest is 1.3.265)
- Now extract the zip file somewhere you remember. Now you have the emulator ready to run, but it still needs Firmware and keys
>[!TIP]
> This is completely optional, but you can easily make a desktop shortcut of the emulator by:
>	- Right clicking on the .exe
>	- Going with your cursor onto "send to…"
>	- Clicking on "create Desktop shortcut"

# Installing prod.keys & title.keys and Firmware
>[!NOTE]
> Before proceeding, make sure you have all of the files above, as I won't cover how to obtain them for legal reasons.
Be sure to extract your keys files if you only have a .zip!

- Open the Ryujinx.exe file. 
>[!NOTE]
> Note that it's gonna open a terminal too, THAT'S COMPLETELY NORMAL as it uses that to collect infos in case the emulator crashes when playing.

It's gonna show a pop-up telling you that keys are missing.

![no keys found](https://github.com/user-attachments/assets/64c14d16-b2ec-4997-8e89-c62ebeb70697)

- Click on "OK" anyway, as we're gonna install them.

- Click on "Action" above, and with your cursor on "Install keys	>".

![install keys](https://github.com/user-attachments/assets/471d2e53-8723-4def-8e33-fd8c418fe55a)

You can now choose either the installation through the direct file or through the "Prod keys" folder. We're gonna cover the second option.

- A new window will appear, you'll have to find the directory of your prodkeys folder; when you've found it, single-click it to select it, and click on "Select folder" below.

![prodkeys selection](https://github.com/user-attachments/assets/aeefc1b1-d173-4321-980d-37234b61770a)

> [!NOTE]
> This image is in Italian, but it should look like this.

Now your keys are setup! Repeat this exact process but with files related to "Firmware" instead. Note that in this case you'll be able to keep your files as a .zip, the reason is explained through the image below.

![install firmware](https://github.com/user-attachments/assets/51b2b2e5-48d1-4ccc-bfb5-3d2c1147b5a2)

# Setting up your games, DLC and Updates folder.
Before doing that, be sure to re-order your switch game files, with DLCs and Updates placed in their folders. This is my setup recommendation:

![games setup](https://github.com/user-attachments/assets/0f21bd21-097c-4262-b2f0-2793f28a3428)

- Go into the settings, from the "Options" tab above as in this image

![settings](https://github.com/user-attachments/assets/d21db783-986d-4b6b-ab6a-622e94e85e0b)

> It'll open a new window
- From the new window, choose "Add" in the "Game Directories" section, there will be another window and from there you'll have to find your switch games folder. Once you've found it, single-click on it to select it, and click on "Select folder" below.

- Do the exact same thing for DLCs and Updates from the "Autoload DLC/Update Directories" section.
when you're done, it's gonna look like this:

![all set](https://github.com/user-attachments/assets/5685a858-9327-4edf-8a94-cdae4ff061f5)

- Click on "Apply" below and then on "OK". If it shows the message as the message below, you've successfully set it up and ready to play!

![success1](https://github.com/user-attachments/assets/975a86e5-b864-4e3e-9693-2224b37425bc)

# Moving your Animal Crossing: New Horizons save from a Yuzu-based emulator

I'll cover how to move your progress from any Yuzu-based emulator (Eden or Citron in most cases) to Ryujinx. The process from the other emulator is the exact same for every possible kind you've been using, but I'll use Eden as an example. 

> [!CAUTION]
> SKIP THIS METHOD AS IT IS NOT WORKING AT THE MOMENT

(In Ryujinx)
- Right click on Animal Crossing and click on "Open Device Save Directory". This will create the shortcut to the save files of the game. You can close the window that appeared.

(In Eden)
- Right click on Animal Crossing and click on "Link to Ryujinx" and if you followed these steps correctly you'll see this pop-up:

![link window](https://github.com/user-attachments/assets/3c4a937d-c88f-4422-8e26-46bc0993959b)


- Click "From Eden"
If you get no errors and a pop-up says "successfully linked" then you're good to go!

### WORKING METHOD

(In Eden)
- Right click on Animal Crossing and click on "Open Save Data Location". This will open a new window with all your ACNH save files.
- Move all of the files you see somewhere you can remember, we're going to move them into the Ryujinx folder.

(In Ryujinx)
- Right click on Animal Crossing and click on "Open Device Save Directory". This will create the shortcut to the save files of the game.
- Move the save files you've backed up into the Ryujinx directory. It's going to look like this:

![save setup](https://github.com/user-attachments/assets/8cdf34fb-4493-44ae-8828-5292fc517b8d)


If you've done everything correctly you'll be able to see this when opening the game!

![success 2](https://github.com/user-attachments/assets/83c6a773-073f-4a8e-839e-92bb18b0d7c3)

You'll be able to see your resident's data, who's linked to the save file. Follow the in-game instructions and you're all set!

> [!IMPORTANT]
> If you're not there already, and if you consider our effort, we would really appreciate if you joined our [Animal Crossing Discord server](https://discord.gg/actreasurehub). We have a really cozy and nice community, owned by @melymels94, with the help of the co-owner @agusguzi and our head mod [Kristy](https://github.com/rice-krispy2). We'll be very happy to see new faces around :D
