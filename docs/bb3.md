# Installing BannerBomb3

1. Open the [BB3 Injector](https://3dstools.nhnarwhal.com/#/bb3gen)
2. Upload your `movable.sed`
3. Click "Build and download"
    - This will download a file called `F00D43D5.bin` and another file named `bb3.bin` inside of a ZIP file.
4. Copy the `bb3.bin` file to the root of your SD.
5. Navigate to the `ID1` this is inside of your `ID0`. It also has a very long name of random characters.
6. Create a folder named `Nintendo DSiWare` inside of the `ID1`. Make sure you name is correct or the exploit will not work.
7. Copy the `F00D43D5.bin` file to the `Nintendo DSiWare` directory.

# UnSafeMode

## Downloads

- [SafeB9SInstaller](https://github.com/d0k3/SafeB9SInstaller/releases/download/v0.0.7/SafeB9SInstaller-20170605-122940.zip)
- [boot9strap](https://github.com/SciresM/boot9strap/releases/download/1.4/boot9strap-1.4.zip)
- [Luma3DS](https://github.com/LumaTeam/Luma3DS/releases/latest) (The `Luma3DS.zip` file)
- [usm.bin](https://github.com/LumaTeam/Luma3DS/releases/latest)

## Moving some files

1. Insert the SD card into your computer.
2. Copy the `boot.firm` and `boot.3dsx` from the `Luma3DS.zip` to the root of your SD card.
3. Create a folder named `boot9strap` and copy the `boot9strap.firm` and `boot9strap.firm.sha` from the `boot9strap.zip` into the folder you just created.
4. Copy the `SafeB9SInstaller.bin` from the `SafeB9SInstaller.zip` file to the root of your SD card.

## Doing the BB3 exploit

You will finese the 3DS security by using an entrypoint in the DSiWare managment menu.

1. With the SD card inserted, launch the System Settings app;
2. Navigate to `Data Managment` > `DSiWare` > `SD card`
    - From here, you should the BB3 multihax menu
3. Launch the BB3 Multihax menu
4. Use the dpad and click `Install unSAFE_MODE`

## Actually booting into USM

You will enter a menu that is pre-baked on all 3DS consoles where you will install B9S!

1. With your console off, hold down these buttons `Left Shoulder` + `Right Shoulder` + `DPad Up` + `A` and keep these down while holding the power button.
2. Press "Okay" to accept the update. (There is no update)
3. Press "I accept" under TOS
4. The update will fail with error code `003-1099`, This is supposed to happen
5. It will prompt you with "Would you like to configure internet settings?" press "Yes"
6. It will give you a new menu, on here navigate to `Connection 1` > `Change Settings` > `Next Page` > `Proxy Settings` > `Detailed Setup`
7. If all went good, you should be in the SafeB9SInstaller.

## Installing Boot9Strap
Here, you will finally get CFW!

1. If prompted, input the Key Combo given on the screen and then press `A` to reboot your device.
2. You should have booted into the Luma Config Menu. From here press `Start`

Congratulations! You've installed CFW

> [Continue](finalizing)
