![](https://github.com/Drazden/heartlandredux/blob/master/imgTitle.png)

### Documentation and Instructions for Heartland Redux 1.0+, Wabbajack 3.5.0.1+

Welcome to Heartland Redux! This modlist is a fork of [Heartland](https://github.com/TDarkShadow/heartland/tree/master), originally created by Sam, which in turn was based off [Bevilex's Modlist for Oblivion](https://www.nexusmods.com/oblivion/mods/47591). Heartland has seen many changes through the years (it was one of the first Wabbajack modlists at launch!), but at its core it has remained a comprehensive graphical overhaul for The Elder Scrolls Oblivion. Redux was created by Drazden to be streamlined, sustainable, and simple.


## Installation  

### Prerequisites:
*   A **vanilla copy of Oblivion** in the **English language** with at least the Knights of the Nine and Shivering Isles DLCs, **obtained from [Steam](https://store.steampowered.com/app/22330/The_Elder_Scrolls_IV_Oblivion_Game_of_the_Year_Edition/) or [GOG](https://www.gog.com/en/game/elder_scrolls_iv_oblivion_game_of_the_year_edition_deluxe_the)**, and **installed outside of C:\Program Files**.
*   Ensure that your Oblivion copy is unmodified. You may have files leftover from old modlists that you need to delete (especially ENB).
*   **Default Oblivion configuration files**. To generate them, first ensure that the `Documents/MyGames/Oblivion` folder has been wiped, then **launch the game once in vanilla**.
*   Around **75GB free storage space**.
    *   6 GB for Oblivion itself.
    *   22 GB for the mod downloads.
    *   47 GB for the modlist installation.
*   A Nexus Premium account, or a lot of time to download the mods manually!

### Using the Wabbajack Autoinstaller

1. **Download** the latest version of Wabbajack from the [Wabbajack Github](https://github.com/wabbajack-tools/wabbajack/releases/latest), and **place the Wabbajack.exe** file to a new directory called **Wabbajack**, as close to the root of your drive as possible (e.g. `C:\Wabbajack` or `C:\Modding\Wabbajack`).
2. **Create a new folder** for the modlist installation, and call it **Heartland**, placing it close to the root of your drive once again, but not within the Wabbajack folder (e.g. `C:\Heartland` or `C:\Modding\Heartland`).
Ensure you have at least 75GB of hard drive space.
1. **Launch Wabbajack.exe** from within the Wabbajack folder. Click **Browse Modlists**, and enable **Show Unofficial Lists**. Locate the **Heartland** modlist in the gallery and click the **Download and Install** button in the corner.
     * Alternatively, the modlist can be downloaded manually from [the Releases tab](https://github.com/Drazden/heartlandredux/releases/latest). If installing manually, place the modlist file in the Wabbajack directory, and select **Install from Disk**.
2. Under Installation Location, **select the Heartland folder** you created in step 2.
If Wabbajack hasn't done so already, set the Download Location to Heartland\downloads (e.g. `C:\Heartland\download` or `C:\Modding\Heartland\downloads`).
1. Click **Begin**.
2. Wabbajack will open a browser and ask for Nexus authorisation. Log in and then hit **Authorise.** (_If you get an error on authorisation, download and install [.Net Framework 4.8](https://dotnet.microsoft.com/download/dotnet-framework/net48) and run the installer again_)
3. Wabbajack will now download and install the mods specified in the installer. The download size is approximately 22 GB so this may take a little while. The installer should keep you informed of progress.
4. After the **installation complete** message appears, close the installer.

### Game Folder Files

Within the Heartland folder, copy the contents of the **Game Folder Files** folder to your root Oblivion directory (e.g. `C:\Steam\steamapps\common\Oblivion`).

#### _Steam and Retail Users_

Only applicable if you have a Steam or retail copy of Oblivion. GOG users can skip this step.

* A file named '4gb patch.exe' should have been copied with the **Game Folder Files**
* Target both the **Oblivion.exe** and **OblivionLauncher.exe** executables in your root Oblivion directory. Both executables will now have been patched to improve the memory that can be allocated to their processes.

### BSA Decompression  

This step is not strictly required, but may improve your performance.  

1. In your Heartland installation, navigate to the **Tools** folder and then the **Oblivion BSA Decompressor** folder.
2. Run **Oblivion BSA Decompressor.exe**.
3. Point it to your Oblivion installation and let it run  .

Typically this will reduce stuttering and load times by removing outdated 2006 zlib compression. This may mean your Oblivion installation will take up slightly more storage space.

## Post Installation 

### Running the Game
1. If you use Steam, ensure it is running.
2. To play the game, select **Oblivion** in the MO2 **executable dropdown** and hit **Run.** **You do not need to add OBSE to MO2. MO2 will automatically load OBSE when selecting Oblivion**.
3. You're ready to go! Check the optional steps below if you would like to further enhance your experience.

### Profiles

The Heartland modlist overhauls visuals and stability, leaving the gameplay systems (questing, levelling, level scaling, combat) in a vanilla state. Certain mods that may be considered 'visual' have also been omitted. Mods that replace vanilla assets or modify vanilla locations (like Better Cities) will typically need to be patched in the same way gameplay mods are.  

- The *Lite* profile is designed to be as compatible as possible. Beyond bug fixes, very little of the base game data has been modified.
- The *Full* profile has more features but is less compatible with new mods. You will need to patch additional mods you add as NPCs, weathers, weapons, and more have been modified. This profile also requires the deluxe edition DLC (Horse Armor and player homes).  

### Extra Notes

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
5. _Characters in my game are bald, or their hair is transparent._  
   * This is an occasional error with Oblivion Reloaded Combined and certain graphics cards. In MO2, navigate to Oblivion Reloaded Combined (ORC) under the Oblivion Reloaded Separator. Delete the `Extra Shaders` folder in `Shaders/ORC`  

## Credits

* **Bevilex** for their fantastic visual overhaul and guide
* **Sam** for the original port of Bevilex's guide and subsequently Heartland
* **Halgari** for the innovative Wabbajack tool
* **Foxman** for this handy readme template and his help with testing
* **jdsmith2816** and **WOJO** the OG Wabbajack Oblivion modders
* My good friend, **TDarkShadow**, for stewarding this list despite having no knowledge of Oblivion
* **iam5** for relentless dedication to support for this list
* **1Mac** and **Dispensation** for compiling helpful information in their modding guides  
* **Aerialvas**, **Peria**, and **Mr.Vanato** for their useful optimisation tips and troubleshooting assistance in the heartland-support channel
* All the testers and users who have taken time to provide feedback: **Seear**, **Aronax**, **epixxor**, **Duriel**, **Foxman**, **Aerialvas**, **Peria**, **ShadowFyre**, **Mr.Vanato**, **Nazo**, **Stormline**, **MrG**, **carl**, **KatieLW19**,  **KarmasLives22**, **ELDYLO**, **Severance**, **Zierry**, **Gatonegro**, **Bartun**, **b e e g y o s h i**, **Epic**, **NaterOfTheWired** and more!
