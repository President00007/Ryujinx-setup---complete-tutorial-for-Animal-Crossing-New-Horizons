In this tutorial, i'll explain in detail how to fully set up your Ryujinx emulator
If you came from the [Ryujinx setup tool] you can skip to the ["setup save" section of this readme](https://github.com/President00007/Ryujinx-setup---complete-tutorial-for-Animal-Crossing-New-Horizons/blob/main/README.md#moving-your-animal-crossing-new-horizons-save-from-a-yuzu-based-emulator)

# Installing the emulator program
- The first thing you need is, of course, the emulator. Be sure to go into [the official Ryujinx site](https://github.com/Ryubing) and select the red "canary" option as in this image.
![canary version selection](https://private-user-images.githubusercontent.com/233430140/566330881-180731db-3f47-43b6-ac15-f0066d532313.png?jwt=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3NzM5MzI5NjgsIm5iZiI6MTc3MzkzMjY2OCwicGF0aCI6Ii8yMzM0MzAxNDAvNTY2MzMwODgxLTE4MDczMWRiLTNmNDctNDNiNi1hYzE1LWYwMDY2ZDUzMjMxMy5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjYwMzE5JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI2MDMxOVQxNTA0MjhaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0xMWYxZDhmNmQ4Nzk5NmZkNjA2NWY2Y2I0MjFjN2E3MGQ0YTY3YzZmOWJhYWQ5YjQyZDMzYzBmZjkzODQ1OTBmJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.EGLW3-l7T6I08QK8NcCdoppgmtYTHSQn9-saoE58C28)
It should download a file called "ryujinx-canary-VERSION-OPERATINGSYSTEM.zip" (as of writing the latest is 1.3.265)
- Now extract the zip file somewhere you remember. Now you have the emulator ready to run, but it still needs Firmware and keys

	This is completely optional, but you can easily make a desktop shortcut of the emulator by:
	- Right clicking on the .exe
	- Going with your cursor onto "send to…"
	- Clicking on "create Desktop shortcut"

# Installing prod.keys & title.keys and Firmware
>[!NOTE]
> Before proceeding, make sure you have all of the files above, as I won't cover how to obtain them for legal reasons.
Be sure to extract your keys files if you only have a .zip!

- Open the Ryujinx.exe file. 
>[!NOTE]
> Note that it's gonna open a terminal too, THAT'S COMPLETELY NORMAL as it uses that to collects infos in case the emulator crashes when playing.
It's gonna show a pop-up telling you that keys are missing.
![keys not found](<img width="455" height="299" alt="keys not found" src="https://github.com/user-attachments/assets/25c49050-6aa0-4c11-a669-f90ea856fefd" />)
- Click on "OK" anyway, as we're gonna install them.

- Click on "Action" above, and with your cursor on "Install keys	>".
![keys installation step](<img width="669" height="221" alt="keys installation" src="https://github.com/user-attachments/assets/3f10e3a0-ed8d-4982-bcb5-b0788973752c" />)
You can now choose either the installation through the direct file or through the "Prod keys" folder. We're gonna cover the second option.

- A new window will appear, you'll have to find the directory of your prodkeys folder; when you've found it, single-click it to select it, and click on "Select folder" below.
![keys folder selection](<img width="948" height="588" alt="keys folder selection" src="https://github.com/user-attachments/assets/ddc961ab-609c-46e9-9af4-984252c4a02e" />)
> [!NOTE]
> This image is in Italian, but it should look like this.

Now your keys are setup! Repeat this exact process but with files related to "Firmware" instead. Note that in this case you'll be able to keep your files as a .zip, the reason is explained through the image below.
![firmware installation step](<img width="730" height="212" alt="firmware installation step" src="https://github.com/user-attachments/assets/d341f376-983d-4d64-a1c2-10a5b64f239b" />)

# Setting up your games, DLC and Updates folder.
Before doing that, be sure to re-order your switch game files, with DLCs and Updates placed in their folders. This is my setup recommendation:
![games setup](<img width="1170" height="455" alt="games setup" src="https://github.com/user-attachments/assets/56262f3c-fc90-4f9a-bd85-1a15e3e3f616" />)

- Go into the settings, from the "Options" tab above as in this image
![settings](<img width="374" height="286" alt="settings" src="https://github.com/user-attachments/assets/61439fd5-c186-4831-8422-40b573d011fe" />)
	It'll open a new window
- From the new window, choose "Add" in the "Game Directories" section, there will be another window and from there you'll have to find your switch games folder. Once you've found it, single-click on it to select it, and click on "Select folder" below.

- Do the exact same thing for DLCs and Updates from the "Autoload DLC/Update Directories" section.
when you're done, it's gonna look like this
![all set](<img width="1525" height="914" alt="all set" src="https://github.com/user-attachments/assets/02d4a781-6950-49f8-8c32-b166154f3dbf" />)

- Click on "Apply" below and then on "OK". If it shows the message as the message below, you've successfully set it up and ready to play!
![success](<img width="1139" height="669" alt="success" src="https://github.com/user-attachments/assets/14694a08-b1fc-4a01-b543-1c9ba879141d" />)

# Moving your Animal Crossing: New Horizons save from a Yuzu-based emulator

I'll cover how to move your progress from any Yuzu-based emulator (Eden or Citron in most cases) to Ryujinx. The process from the other emulator is the exact same for every possible kind you've been using, but I'll use Eden as an example. 

> [!CAUTION]
> SKIP THIS METHOD AS IT IS NOT WORKING AT THE MOMENT
(In Ryujinx)
- Right click on Animal Crossing and click on "Open Device Save Directory". This will create the shortcut to the save files of the game. You can close the window that appeared.
(In Eden)
- Right click on Animal Crossing and click on "Link to Ryujinx" and if you followed these steps correctly you'll see this pop-up:
![ryujinx link](<img width="406" height="210" alt="ryujinx link" src="https://github.com/user-attachments/assets/bb58b131-3be2-4f64-98a6-1e9125bbe6b9" />)

- Click "From Eden"
If you get no errors and a pop-up says "successfully linked" then you're good to go!

WORKING METHOD
(In Eden)
- Right click on Animal Crossing and click on "Open Save Data Location". This will open a new window with all your ACNH save files.
- Move all of the files you see somewhere you can remember, we're going to move them into the Ryujinx folder.
(In Ryujinx)
- Right click on Animal Crossing and click on "Open Device Save Directory". This will create the shortcut to the save files of the game.
- Move the save files you've backed up into the Ryujinx directory. It's going to look like this:
![files setup](<img width="1163" height="470" alt="files setup" src="https://github.com/user-attachments/assets/1750c511-4da9-4c26-a8f6-611501344485" />)

If you've done everything correctly you'll be able to see this when opening the game!
![second success](<img width="1001" height="659" alt="second success" src="https://github.com/user-attachments/assets/85669c6c-af65-4947-b01b-7950061f7eeb" />)
You'll be able to see your resident's data, who's linked to the save file. Follow the in-game instructions and you're all set!

> [!IMPORTANT]
> If you're not there already, we'd appreciate if you joined our [Animal Crossing Discord server](https://discord.gg/actreasurehub).
