![](https://github.com/Drazden/heartlandredux/blob/master/imgTitle.png)

### Documentation and Instructions for Installer Version 1.0, Wabbajack 3.5.0.1+

**NOTE**: Welcome! Before we get started, a note: if you encounter issues with your installation, the Heartland support channel can be found on (Heartland Modlist Support)[xx]. Please direct any and all support queries there.

## Mandatory Instructions

#### Prerequisites:
*   A **vanilla copy of Oblivion** in the **English language** with at least the Knights of the Nine and Shivering Isles DLCs, **obtained from [Steam](https://store.steampowered.com/app/22330/The_Elder_Scrolls_IV_Oblivion_Game_of_the_Year_Edition/) or [GOG](https://www.gog.com/en/game/elder_scrolls_iv_oblivion_game_of_the_year_edition_deluxe_the)**, and **installed outside of C:\Program Files**.
*   **Default Oblivion configuration files**. To generate them, first ensure that the `Documents/MyGames/Oblivion` folder has been wiped, then **launch the game once in vanilla**.
*   Around **50GB free storage space**.
    *   6 GB for Oblivion itself.
    *   xx GB for the mod downloads.
    *   xx GB for the modlist installation.
*   A Nexus Premium account, or a lot of time to download the mods manually!

### Using the Wabbajack Autoinstaller

1. **Download** the latest version of Wabbajack from the [Wabbajack Github](https://github.com/wabbajack-tools/wabbajack/releases/latest), and **place the Wabbajack.exe** file to a new directory called **Wabbajack**, as close to the root of your drive as possible (e.g. `C:\Wabbajack` or `C:\Modding\Wabbajack`).
2. **Create a new folder** for the modlist installation, and call it **Heartland**, placing it close to the root of your drive once again, but not within the Wabbajack folder (e.g. `C:\Heartland` or `C:\Modding\Heartland`).
Ensure you have at least xxGB of hard drive space.
1. **Launch Wabbajack.exe** from within the Wabbajack folder. Click **Browse Modlists**, and enable **Show Unofficial Lists**. Locate the **Heartland** modlist in the gallery and click the **Download and Install** button in the corner.
     * Alternatively, the modlist can be downloaded manually from [the Releases tab](https://github.com/Drazden/heartlandredux/releases/latest). If installing manually, place the modlist file in the Wabbajack directory, and select **Install from Disk**.
2. Under Installation Location, **select the Heartland folder** you created in step 2.
If Wabbajack hasn't done so already, set the Download Location to Heartland\downloads (e.g. `C:\Heartland\download` or `C:\Modding\Heartland\downloads`).
1. Click **Begin**.
2. Wabbajack will open a browser and ask for Nexus authorisation. Log in and then hit **Authorise.** (_If you get an error on authorisation, download and install [.Net Framework 4.8](https://dotnet.microsoft.com/download/dotnet-framework/net48) and run the installer again_)
3. Wabbajack will now download and install the mods specified in the installer. The download size is approximately xx GB so this may take a little while. The installer should keep you informed of progress.
4. After the **installation complete** message appears, close the installer.

### Game Folder Files

Within the Heartland folder, copy the contents of the **Game Folder Files** folder to your root Oblivion directory (e.g. `C:\Steam\steamapps\common\Oblivion`).

### Special Installation Steps

##### _Steam and Retail Users_

Only applicable if you have a Steam or retail copy of Oblivion. GOG users can skip this step.

* A file named '4gb patch.exe' should have been copied with the **Game Folder Files**
* Target both the **Oblivion.exe** and **OblivionLauncher.exe** executables in your root Oblivion directory. Both executables will now have been patched to improve the memory that can be allocated to their processes.


### Running the Game
1. If you use Steam, ensure it is running.
2. To play the game, select **Oblivion** in the MO2 **executable dropdown** and hit **Run.** **You do not need to add OBSE to MO2. MO2 will automatically load OBSE when selecting Oblivion**.
3. You're ready to go! Check the optional steps below if you would like to further enhance your experience.

## Optional Post Installation Instructions

### Heartland Optionals

This list includes several optional configurations pre-installed, which can be swapped in and out as desired. Each configuration is denoted by an MO2 mod separator, which includes step-by-step instructions on how to enable the optional mods. To view, simply right click the seperator select Information, then select the Notes tab. You will be presented with instructions like below:

### Mod Suggestions, Gameplay Profiles, and Installing Additional Mods

The base Heartland modlist overhauls visuals and stability, leaving the gameplay systems (questing, levelling, level scaling, combat) in a vanilla state. Certain mods that may be considered 'visual' have also been omitted. Mods that replace vanilla assets or modify vanilla locations (like Better Cities) will typically need to be patched in the same way gameplay mods are.  
Given this, you may want to consider adding additional mods to enhance Oblivion's gameplay. Below are some general steps to follow in order to add mods on top of the list. Please note though, we cannot provide support for list modifications, so you are more than welcome to play around, but do so at your own risk!

#### General Steps


## Extra Notes

*   Due to the way MO2 loads Oblivion and OBSE, the Steam overlay and screenshot functionality cannot be used. Use F11 to take screenshots using Oblivion Reloaded.

## Troubleshooting

1. _Wabbajack says download X failed, what now?_
   - For vanilla game files such as 'Oblivion - Meshes.bsa', ensure that your game is unmodified and in English.
   - For other files, restart Wabbajack (or your PC) and attempt installing the modlist again.
   - If it still fails, check in with the [Heartland Modlist Support] server.
2. _I can’t run the Oblivion executable from MO2 - I get an application error._
    * If you bought the game through Steam, it needs to be running in the background for you to play the game. Boot up Steam and give it another try.
3. _When I run Oblivion, a new window opens and I can hear the main menu audio, but all I get is a blank/black screen._
   * MO2 is failing to load the OBSE libraries when running Oblivion leading to issues with the mods installed. To correct, click the executable dropdown in MO2, select Edit, and then check the Oblivion.exe entry. Ensure that Force Load Libraries is ticked, and click Configure Libraries. Ensure that Oblivion.exe is set to load the library obse_1_2_416.dll in your Oblivion game directory.
4. _Following the above instructions, there is no obse_1_2_416.dll._
   * Make sure you have copied the contents of Game Folder Files to your Oblivion game directory. The OBSE files should be present in this folder.

## Credits

* **Bevilex** for their fantastic visual overhaul and guide
* **Sam** for the original port of Bevilex's guide and subsequently Heartland
* **Halgari** for the innovative Wabbajack tool
* **Foxman** for this handy readme template and his help with testing
* **jdsmith2816** and **WOJO** the OG Wabbajack Oblivion modders
* My good friend, **TDarkShadow**, for stewarding this list despite having no knowledge of Oblivion
* **iam5** for relentless dedication to support for this list
* **Aerialvas**, **Peria**, and **Mr.Vanato** for their useful optimisation tips and troubleshooting assistance in the heartland-support channel
* All the testers and users who have taken time to provide feedback: **Seear**, **Aronax**, **epixxor**, **Duriel**, **Foxman**, **Aerialvas**, **Peria**, **ShadowFyre**, **Mr.Vanato**, **Nazo**, **Stormline**, **MrG**, **carl**, **KatieLW19**,  **KarmasLives22**, **ELDYLO**, **Severance**, **Zierry**, **Gatonegro**, **Bartun**, **b e e g y o s h i**, **Epic**, **NaterOfTheWired** and more!
