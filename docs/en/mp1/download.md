!!! note
    Updated Classic DOESN'T require original game or Steam. You can install a build and play Updated Classic without Steam.

    We have a build versioning that helps track changes and allows end users to determine how up to date their version is.. 
    
    Right now, ^^Build 5^^ is available for **Max Payne**.

You can download here : [Mega](https://mega.nz/folder/7kJlRTBB#K-cStm8937nBzmtjXDTW1Q) / [Google Drive](https://drive.google.com/drive/folders/1UkD1eL_jFrvIlXOMgbETjYXxHTv0VrLF) (Size: 1.12 GB)

## Install
Build works perfectly without Steam. But, if you want to play it through Steam, then follow the instructions below.    

So, you downloaded the archive and do not know what to do next.

1. **Remove the Steam Version:**  
    First, you need to remove all files from the original Steam version of the game. 

    To do this, click on the `Max Payne` with the right mouse button in your `Steam library` and select `Properties` > `Local Files`> > `Browse Local Files`.... After this action you will have to open the folder with the game files. Just delete them all.

2. **Installing Normal Version of the game:**  
Now everything is simple. All you have to do is unpack downloaded build archive, take all the files from it's root directory and move it to your steam-version folder (which must be empty). When you move (or copy) all these files, you'll be ready to play.

!!! note
    If you want to install the build without downloading the Steam version of the game, you can simply use the {++.acf++} file from the archive below, which is responsible for having the installed game on Steam.
Download:
[Mega](https://mega.nz/folder/7kJlRTBB#K-cStm8937nBzmtjXDTW1Q/file/j0xlhDhD) / [Google Drive](https://drive.google.com/file/d/1l6oLgY0KZIvOEtjVGF5ROn8Ngv20FUO8/view?usp=drive_link)

Put file in `Steam\steamapps` folder, after installation, restart Steam.
Content of the archive:

- `appmanifest_210350.acf` - File for Max Payne (RU)
- `appmanifest_12140.acf` - File for Max Payne

## Pre-launch

Recommendations before start the game:

1. **In game launcher select D3D Hardware T&L in Acceleration.**

2. **Make sure, that you have installed all necessary components for the game.**

    If you're not sure about this, you certainly need to visit Readme/Prerequisites and install:

    - DirectX Pack - `ReadMe/Prerequisites/Direct X/DXSETUP.exe`
    - Runtime Pack - `ReadMe/Prerequisites/Runtime Pack/RuntimePack_x86_x64.exe`
    - Visual C++ Redistributable Hybrid - `ReadMe/Prerequisites/Visual C++ Redistributable Hybrid/VCR_Hyb_x86_x64_24.04.2019.exe`

3. **Anti Aliasing.**

    The game's anti aliasing works bad on Hardware mode. The problem is a white lines on geometry in dark places ONLY. Here is how it looks like:

    -------IMAGE-------

    Well, if it's not really bothering you, just skip this part. But if it does bothering you, here is a solution:
    I have Nvidia video card so the only instruction I can give you is how to enable anti aliasing in Nvidia control panel. 
    
    If you've another video cards manufacturer I will really thankful for different instructions for specific video cards manufacturers.

    For Nvidia video cards users:

        1. Open game's launcher, then head to Options... and turn off Antialiasing.
        2. Launch your videocard settings program: Nvidia Control Panel.
        3. Head to Manage 3D settings, then go to Program Settings and Add MaxPayne.exe there.
        4. After adding, you'll see a settings for this application.
        5. Apply following settings:        
            - Antialiasing - Mode: Enhance the application setting
            - Antialiasing - Settings: Maxium that your PC can handle with.
            - Antialiasing - Transparency: Maxium that your PC can handle with.

    -------IMAGE-------

    If it didn't work, apply following setting too (_thanks to Susez!_):
    - `Antialiasing - FXAA: On`

    -------IMAGE-------

4. **Save file location**

    Save game files now stores to `Max Payne/savegames` folder. Your old saves are probably can be founded in `Documents` folder.

5. **Windowed Mode**

    To play with Windowed Mode open file `Max Payne/d3d9.ini` via notepad and change the value of parameter `ForceWindowedMode` to `1`.

6. **Developer Console**

    If you're playing via Steam, go to your Steam game library and click with right mouse bottom on Max Payne then select Properties. In `LAUNCH OPTIONS` box type following commands:
    `-developerkeys -developer`

    If you're playing without Steam, create a shorcut to MaxPayne.exe then click right mouse bottom on shorcut and select Properties. In Target in the end of the line with a space add following commands:
    Make sure that you have quotes at the beginning and at the end of the line!
    `-developerkeys -developer`

7. **Black-borders**

    If you like to disable black-borders in cutscenes, open the file `Max Payne/scripts/MaxPayne.WidescreenFix.ini` via notepad and change value of parameter C`utsceneBorders` to `1`.

8. **Screenshots**

    You can enable in-game screenshot feature. Just do same steps as in (Developer Console) but this time only code you need is: `-screenshot`
    Press F10 in game to take a screenshot! They will be store to `Max Payne/screenshots` folder.

9. **Ultra widescreen**

    How to play in 21:9 mode (or another that not listed in launcher)
    You need to open Registry Editor (use regedit in search on taskbar or in 'run' window.)
    Go to `Computer\HKEY_CURRENT_USER\SOFTWARE\Remedy Entertainment\Max Payne\Video Settings`.
    Edit values of parameters `Display Height` and `Display Width` - Make sure that you selected `DECIMAL` base when editing them! - put a values of your monitor resolution.

    !!! note ""
            Dipslay Height = 1080
            Display Width = 2560


    Do same steps as in (Developer Console) but this time only code you need is: `-nodialog`

10. **If the music are not playing on Windows 11** _(thanks to Stainless!)_

    - Download the latest version of IndirectSound: https://www.indirectsound.com/
    - Unpack downloaded archived.
    - Put files d3d9.dll and d3d9.ini into game folder (near MaxPayne.exe file).