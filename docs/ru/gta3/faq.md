# Frequently Asked Questions

<!-- ![alt](../../assets/gta3/faq.png) -->

In this section, you may be able to find answers to some questions related to the build (the list will be updated).

??? note "Can I install third-party modifications to the build?"
    Yes, but please note that this can cause various technical problems/issues and you will lose our support in these matters.

??? note "Which Windows versions are supported?"
    Windows 7 SP1, 8 and 10.

??? note "Will there be Liberty Unleashed or Multi Theft Auto support?"
    Not planned.

??? note "The game is very slow"
    1. In file Grand Theft Auto 3/scripts/GTA3.WidescreenFix.ini set for parameter **ForceMultisamplingLevel** value 0.
    2. Delete file Grand Theft Auto 3/mss/scrlog.asi.

    ==WARNING! If you'll complete a second step - there is will problems with support!==

??? note "When the game starts, the window with the message "AppId is not configured." comes out."
    Delete the file Grand Theft Auto 3/mss/GInputIII.asi.
    
    Note: After this, support for gamepad will be lost.

??? note "Game doesn't launch or black screen after launch / When resolution setting identical to the resolution of the monitor, the game freeze/crashes / Error: Cannot find "1x1x1" video mode."
    1. In properties of gta3.exe go to Compatibility, select Change high DPI settings and turn ON following parameters:
    "Program DPI: when I open this program"
    "High DPI scaling override: Application".
    2. In the file Grand Theft Auto 3/scripts/GTA3.WidescreenFix.ini in the parameters ResX and ResY set the resolution values of your monitor.
    Example:
        `ResX = 1920`
        `ResY = 1080`
    3. Install DirectPlay.
    4. Delete file My Documents/GTA3 User Files/gta3.set.
    5. Set the compatibility with Windows XP SP3 (for example).

??? note "Intro movies don't work."
    Set Compatibility with Windows XP Service Pack 3 and install codecs.

??? note "When I start the game, I get the Could not detect game version and/or This game is not supported errors."
    Delete the file:
    Grand Theft Auto 3/scripts/modloader.asi
    Note: After this, some addons will not work.

??? note "How do I activate the tips with the PS2 gamepad buttons?"
    In the Grand Theft Auto 3/mss/GInputIII.ini file, set the "PlayStationButtons" value to 1.

??? note "When I try to extract files from the archive, it gives me an error: Can not open file or Archive corrupted."
    Update your archiver or use another.

??? note "How to enable/disable the "black borders" in cutscenes?"
    In Display Setup (in game) turn on "Wide screen" feature.

??? note "When launched via Steam, the game crashes without error after the intro clips."
    Make sure that the game and Steam are installed on the same drive.

??? note "How to setup controls on gamepad?"
    In the mss/GinputIII.ini file, you need the "ControlsSet" option. All available control "sets" can be found in the file ReadMe/Ginput docs/GAME CONTROLS FULL LIST.txt.

??? note "I have a resolution different than 16:9, the menu screens and loadscreens do not fit on the monitor."
    Open file Scripts/GTA3.WidescreenFix.ini, find ForceAspectRatio and FrontendAspectRatio parameters, then change it's value to your aspect ratio.
    Example:
    ```ForceAspectRatio = 16:10
    FrontendAspectRatio = 16:10```

??? note "Which languages are supported by this build?"
    English, French, German, Italian, Spanish and Russian.

??? note "I like to return a blur like on PS2 version."
    Delete file Scripts/SharpTrails.asi.

??? note "An error before startup: "Unable to load rundll32exefix.asi. Error: 193""
    Move rundll32exefix.asi file from scripts folder to mss folder.

??? note "What version of the game is the Updated Classic based on?"
    1.0

??? note "Game crashing at loading screens."
    Make sure that your anti-virus didn't delete any game files. Add a game folder to exceptions and reinstall build.

![alt](../../assets/gta3/char_0008.png) 