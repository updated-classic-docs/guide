!!! note
    Updated Classic DOESN'T require original game or Steam. You can install a build and play Updated Classic without Steam.

    We have a build versioning that helps track changes and allows end users to determine how up to date their version is.. 
    
    Right now, ^^Build 6^^ is available for **Max Payne 2**.

You can download here : [Mega](https://mega.nz/folder/7kJlRTBB#K-cStm8937nBzmtjXDTW1Q) / [Google Drive](https://drive.google.com/drive/folders/1UkD1eL_jFrvIlXOMgbETjYXxHTv0VrLF) (Size: 1.73 GB)

## Install
Build works perfectly without Steam. But, if you want to play it through Steam, then follow the instructions below.    

So, you downloaded the archive and do not know what to do next.

1. **Remove the Steam Version:**  
    First, you need to remove all files from the original Steam version of the game. 

    To do this, click on the `Max Payne 2 The Fall of Max Payne` with the right mouse button in your `Steam library` and select `Properties` > `Local Files`> > `Browse Local Files`.... After this action you will have to open the folder with the game files. Just delete them all.

2. **Installing Normal Version of the game:**  
Now everything is simple. All you have to do is unpack downloaded build archive, take all the files from it's root directory and move it to your steam-version folder (which must be empty). When you move (or copy) all these files, you'll be ready to play.

!!! note
    If you want to install the build without downloading the Steam version of the game, you can simply use the {++.acf++} file from the archive below, which is responsible for having the installed game on Steam.
Download:
[Mega](https://mega.nz/folder/7kJlRTBB#K-cStm8937nBzmtjXDTW1Q/file/j0xlhDhD) / [Google Drive](https://drive.google.com/file/d/1l6oLgY0KZIvOEtjVGF5ROn8Ngv20FUO8/view?usp=drive_link)

Put file in `Steam\steamapps` folder, after installation, restart Steam.
Content of the archive:

- `appmanifest_12260.acf` - File for **Max Payne 2 (RU)**
- `appmanifest_12150.acf` - File for **Max Payne 2 The Fall of Max Payne**

## Pre-launch

Recommendations before start the game:

1. **Hardware acceleration**
    
    In game launcher select D3D Hardware T&L (hardware transform and lighting) in Acceleration.
    
    -------IMAGE-------

2. **Sounds**
    
    There is a problem that some sounds (especially voices) are too quite in comparison to other sounds. If you're not using **Creative SoundBlaster** cards, there is a solution:
    In game launcher go to `Options`... and **disable** `EAX Environmental Effects` and `Multi-channel Audio`:

    -------IMAGE-------

3. **Make sure, that you have installed all necessary components for the game.**

    If you're not sure about this, you certainly need to visit Readme/Prerequisites and install:

    - DirectX Pack - `ReadMe/Prerequisites/Direct X/DXSETUP.exe`
    - Runtime Pack - `ReadMe/Prerequisites/Runtime Pack/RuntimePack_x86_x64.exe`
    - Visual C++ Redistributable Hybrid - `ReadMe/Prerequisites/Visual C++ Redistributable Hybrid/VCR_Hyb_x86_x64_24.04.2019.exe`

4. **Save file location**

    Save game files now stores to `Max Payne 2/savegames` folder. Your old saves are probably can be founded in `Documents` folder.

5. **Windowed Mode**

    To play with Windowed Mode you need to:

    - If you're playing via Steam, go to your Steam game library and click with right mouse bottom on `Max Payne 2 The Fall of Max Payne` then select `Properties`. In `LAUNCH OPTIONS` box type following commands:
        `-window`

    - If you're playing without Steam, **create a shorcut** to `MaxPayne2.exe` then click right mouse bottom on shorcut and select `Properties`. In `Target` in the end of the line with a space add following commands:
        `-window`

6. **Developer Console**

    - If you're playing via Steam, go to your Steam game library and click with right mouse bottom on `Max Payne 2 The Fall of Max Payne` then select `Properties`. In `LAUNCH OPTIONS` box type following commands:
        `-developerkeys -developer`

    - If you're playing without Steam, **create a shorcut** to `MaxPayne2.exe` then click right mouse bottom on shorcut and select `Properties`. In `Target` in the end of the line with a space add following commands:
        `-developerkeys -developer`

7. **Black-borders**

    If you like to disable black-borders in cutscenes, open the file `Max Payne 2/scripts/MaxPayne2.WidescreenFix.ini` via notepad and change value of parameter `CutsceneBorders` to `1`.

8. **Screenshots**

    You can enable in-game screenshot feature. Just do same steps as in (Developer Console) but this time only code you need is: `-screenshot`
    Press `F10` in game to take a screenshot! They will be store to `Max Payne 2/screenshots` folder.

9. **Ultra widescreen**

    How to play in 21:9 mode (or another that not listed in launcher)
    You need to open Registry Editor (use regedit in search on taskbar or in 'run' window.)
    Go to `Computer\HKEY_CURRENT_USER\SOFTWARE\Remedy Entertainment\Max Payne 2\Video Settings`.
    Edit values of parameters `Display Height` and `Display Width` - Make sure that you selected `DECIMAL` base when editing them! - put a values of your monitor resolution.

    !!! note ""
            Display Height = 1080
            Display Width = 2560


    Do same steps as in (Developer Console) but this time only code you need is: `-nodialog`
