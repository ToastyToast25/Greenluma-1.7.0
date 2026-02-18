# Greenluma-1.7.0
Ultimate Steam Bypass

Use this repo for GUI
https://github.com/3vil3vo/GreenLuma-Manager

INDEPTH GUIDE REDDIT LINK
https://www.reddit.com/r/PiratedGames/comments/1pyf0p0/comment/o4y63kb/?context=3

***************************************************************
* GreenLuma 2025 1.7.0                                        *
* by Steam006                                                 *
***************************************************************

GreenLuma 2025 Features:
Unlock not owned games
Unlock not owned DLC
Low Violence bypass
Unlock Stats and Achievements in not owned games (Locally saved only)
Create cracked dedicated online servers in some games (Mainly hlds and srcds)
Denuvo Support (If app ownership ticket (Decrypted + Encrypted) is available)
SteamStub Support (If app ownership ticket (Decrypted) is available)
LumaCEG plugin support
Steam Families restrictions bypass
Region lock bypass
Stealth mode
Support for x64 and x86 games
Support for official Steam client

Stealth mode features:
Unlock not owned Games
Unlock not owned DLC
Low Violence bypass
Family Sharing restrictions bypass
Region lock bypass

Installation:

Normal mode:
1. Backup the original bin\x64launcher.exe.

2. Copy GreenLuma2025_Files, GreenLuma_2025_x86.dll, GreenLuma_2025_x64.dll, GreenLumaSettings_2025.exe, DLLInjector.exe and DLLInjector.ini to your Steam folder and x86launcher.exe to the bin folder.

3. Start Steam with DLLInjector.exe.

Stealth mode (user32.dll):
1. Run DeleteSteamAppCache.exe.

2. Copy user32.dll to your Steam folder.

3. Start Steam.

4. user32.dll and the AppList folder can be deleted after logging in for additional stealth.

5. If games or DLC stop being unlocked, run DeleteSteamAppCache.exe again.

Stealth mode (user32.dll, Steam Families):
1. Run DeleteSteamAppCache.exe.

2. Copy user32SF.dll to your Steam folder.

3. Rename user32SF.dll to user32.dll.

4. Start Steam.

5. user32.dll and the AppList folder can be deleted after logging in for additional stealth.

6. If games or DLC stop being unlocked, run DeleteSteamAppCache.exe again.

Stealth mode (Any folder):
1. Copy GreenLuma_2025_x64.dll, GreenLumaSettings_2025.exe, DLLInjector.exe and DLLInjector.ini to any folder on your PC.

2. Use GreenLumaSettings_2025.exe to set the full paths to Steam.exe and GreenLuma_2025_x64.dll and to enable stealth mode.

3. Start Steam with DLLInjector.exe.

Dedicated server:
1. Copy GreenLuma_2025_x86.dll, GreenLuma_2025_x64.dll, GreenLumaSettings_2025.exe, DLLInjector.exe and DLLInjector.ini to your Server folder.

2. Use GreenLumaSettings_2025.exe to enable server mode.

3. Start the server with DLLInjector.exe.



***************************************************************
* GreenLuma 2025 1.7.0                                        *
* EXTENDED INDEPTH GUIDE ON HOW TO USE                        *
***************************************************************



An Updated Guide For Using Greenluma and Downloading and Unlocking Games/DLC/ETC December 2025-January 2026
Guide
UPDATED 1-5-25 at 1PM EST. See all sections listed UPDATED or CORRECTED. This guide is for 1.7.0 greenluma and lower. The Greenluma author has made it impossible to download with 1.7.1 at this time, saying that if it's continued to be bypassed, he will cease development. If you intend to continue to bypass, please use greenluma 1.7.0 or lower. Sorry the developer is being strict because it's not his intended scope, yet still wants to unlock not owned games.

DISCLAIMER: I(u/therealriddler121) (OP2) and u/Useful-Use-3296 (OP1) am/are not liable for the use of the information here and this guide was strictly provided for informational purposes only on methods that are already publicly findable and available on various platforms (github, youtube, reddit). You agree to waive and hold harmless both OP1 and OP2 of any liability because of use of this guide or loss of account access because of your use with this information.

First off; I want to give a MASSIVE SHOUTOUT to u/useful-use-3296 for this guide you will see below, This is 80% their guide and walkthrough, but I am updating it to contain some information (with their permission) that may be useful to have. Everything that has been italicized and emboldened is my input.

EDITOR's and OP Note: THIS APPLIES TO WINDOWS ONLY.

Per u/useful-use-3296:

"I've been using greenluma to acquire clean steam files for a while now and it's my go to method for when I want to play a new game. I've noticed there isn't much information online on how to use it so I made a guide for anyone to view. Hope this helps someone out there that needs it. Now onto the tutorial."

Install And Setup (Normal Mode & Stealth Mode)
Before I get into the tutorial I would recommend to use a burner steam account and a different steam install location from your main steam install location! WHILE THIS IS RECOMMENDED, IT IS NOT NECESSARY. I (riddler) use a steam burner account and greenluma in stealth mode.

The following information is a basic guide of installing both Normal and Stealth Mode Greenluma (Any Folder Method)

Normal GreenLuma Installation
1. Create a folder for custom steam installation (eg C:\Program Files\Steam Luma) or use your existing steam installation.

2. Now install steam to that location if you made a custom steam installation folder.

3. Then login and install any game and run it once (example, Milky Way Idle) this will create folders that you need later, if you cannot run the game once, it's not a big deal as these folders can auto-generate themselves if done right.

4. Now fully close steam from windows system tray; THIS IS VERY IMPORTANT, STEAM CAN AND WILL OVERWRITE EVERYTHING YOU DO IF YOU DO NOT DO THIS.

5. Backup bin\x86launcher.exe file to a known location; Please always have a backup.

6. Then copy all greenluma files from the normal folder into the steam installation root folder. (eg C:\Program Files\Steam Luma\ or C:\YOURSTEAMINSTALLATION\)

7. Create a folder in steam installation root folder named AppList (!CASE SENSITIVE!)

8. Now Start GreenLumaSettings_2025.exe in steam root folder.

9. Select no questions mode (4).

10. Now select 7 to exit.

GreenLuma STEALTH MODE (ANY FOLDER) Installation - NEW
Stealth mode (Any folder):

1. Copy GreenLuma_2025_x64.dll, GreenLumaSettings_2025.exe, DLLInjector.exe and DLLInjector.ini to any folder on your PC.

2. Use GreenLumaSettings_2025.exe to set the full paths to Steam.exe and GreenLuma_2025_x64.dll and to enable stealth mode.

3. Start Steam with DLLInjector.exe.

EVERYTHING PASSED THIS POINT APPLIES TO BOTH STEALTH MODE/NORMAL MODE GREENLUMA.

Downloading Functionality
Some Understanding
GreenLuma stores IDs in .txt files within the AppList folder but has a hard limit of 130 files.

To properly download games, you must: Create one .txt file containing the App ID. Create one or more .txt files, each containing a single Depot ID (for DLC or additional content).

The .txt files MUST be numbered sequentially:

0.txt → App ID (example 1245620)

1.txt → Depot ID (example 1245621) (required; missing this will cause a "No Licenses" error)

Having the LUA file before adding to the Applist folder makes adding to the Applist folder SIGNIFICANTLY EASIER; See The "getting manifest Files" Section.

NOTE: For some games there can be multiple Depot IDs (example Dark Souls or Nightreign) where each Depot ID references different files. If you come across an error because a File is Missing or "No Licenses", you likely missed a Depot/APP ID.

How To Start Downloading Games
Go to steamdb.info and pick a game.

I am going to use Teardown for example.

Create a txt called 0.txt in AppList Folder and in that file paste the App ID number (App Id can be found on steamdb on the game page. Teardown Id is 1167630)

So for example put 1167630 in File 0.txt In C:\Program Files\Steam Luma\AppList or C:\YOURGREENLUMAINSTALLATION\Applist

Now we have to add the base game depot (game depot contains the game files) so steam will actually download the game files. (if you don't do this then steam will show the game is 0 bytes when you try to downloading the game)

On the Teardown game page on steamdb in the depot tab on the left I can see the base game App ID is 1167634 and the size is 4.18GiB | 2.90 GiB

So make a txt called 1.txt and add 1167634 to the txt file

Now where are going to add two dlcs that I want Teardown: The Greenwash Gambit and Teardown: Quilez R0113R Robot

Go to the dlc tab on game page on steamdb and you can see all the dlcs for the game

I can see the DLCS and IDS are:

Teardown: Time Campers = ID of 2657050

Teardown: Folkrace = ID of 2657060

Teardown: Season Pass = ID of 2657070

Teardown: Quilez R0113R Robot = ID of 2657080

Teardown: The Greenwash Gambit = ID of 2657100

Now we have to add all the DLCS to the AppList folder

2.txt should have 2657050

3.txt should have 2657060

4.txt should have 2657070

5.txt should have 2657080

6.txt should have 2657100

this will install the base game and all 5 DLCS

GETTING MANIFEST FILES/LUA There are many ways to grab manifest files out there. A simple google search using "Steam manifest generator" would yield a lot of results, but out of all I tried... RYUU's is the best. Once there you will need all manifests and the LUA file for the next steps.

Now Onto The Placing The Manifest Files < Corrected
All the manifest files for the game/DLC you are trying to download must be placed in C:\Program Files\Steam Luma\depotcache or C:\YOURSTEAMINSTALLATION\depotcache (Note: sometimes steam randomly deletes these so check if they are still present in the depotcache folder if having trouble getting games to download) and please retain a copy of your manifest files for this reason.

Now Onto Adding The Decryption Key/Keys
So first go to C:\Program Files\Steam Luma\config\config.vdf or C:\YOURSTEAMINSTALLATION\config\config.vdf and edit it with notepad++ or whatever you have. (Make sure steam is fully closed first)

Now go to the folder where you downloaded your manifest files.

In that folder there should be a .lua file. open the .lua file with something like notepad++.

You should see something like this.

addappid(1167630)
addappid(1167634,0,"4e8b0f273a59d1c3b762e4f8a9c5d01e2b63a7f940d58c21e7b3a69f0c4d82e1")
setManifestid(1167634,"4829571036849201735")
addappid(2657050,0,"d17c8a2b905ef34a6c2d7b19e0f5a83c49b0d67f2e15a4c38b9f0d62e7a13c5b")
setManifestid(2657050,"9301746852918470621")
addappid(2657080,0,"9b4e1a7c2d05f38b6e4a9c01d7f23b58a0c9e6b1d4f75a3e28c09f1b3e6d5a72")
setManifestid(2657080,"1758394206715943820")
addappid(2657060,0,"a1d07b4e9f2c58a3e6b1d40c7f39a82e5b0c94f7a1d26e3b58c09f2e4a7b3d65")
setManifestid(2657060,"6042713950826197483")
addappid(2657100,0,"c5b9a2d40f73e1b6a8d5c09f2e7a34b18f6d0e29c1b75a4f3e68b0d5a2c97f14")
setManifestid(2657100,"2910465871938204756")
addappid(2657070)
So the addappid (1167634) is the game depot for files with a size of 4.18GiB | 2.90 GiB from earlier and the decryption key is "4e8b0f273a59d1c3b762e4f8a9c5d01e2b63a7f940d58c21e7b3a69f0c4d82e1". (All decyption keys I randomly generated just for tutorial purposes)

And all the other lines are the dlcs for the game.

IF YOU ARE UNSURE WHETHER THE APP ID/DEPOT ID IS CORRECT; USE STEAMDB TO VERIFY BY SEARCHING THEM.

In the config.vdf that we are currently editing there is a depot section near the bottom that will look like this.

"depots"
{
    "123456789"
    {
        "DecryptionKey" "8e4c9a10b6d5f73e2a1c08f49d7b35e6a2c90b1d4f57e3a6c8b0d29f1e47a53c"
    }                
}
You want to add your decryption key to the list below for EACH APPID/DEPOTID listed in the LUA, if you already have the base game; that key should already be there, do not overwrite it.

"depots"
{
    "123456789"
    {
        "DecryptionKey" "8e4c9a10b6d5f73e2a1c08f49d7b35e6a2c90b1d4f57e3a6c8b0d29f1e47a53c"
    }
    "1167634"
    {
        "DecryptionKey" "KEYHERE"
    }
    "DLC/Depot ID"
    {
        "DecryptionKey" "KEYHERE"
    }
    "DLC/Depot ID"
    {
        "DecryptionKey" "KEYHERE"
    }
    "DLC/Depot ID"
    {
        "DecryptionKey" "KEYHERE"
    }                         
}
Do this for every single APPID/DEPOT ID that your game requires. This has to also be done for any DLC you intend on adding or playing;

Note: DON'T ADD THE FIRST APPID IN THE FIRST LINE OF THE .lua FILE! (Example: don't add addappid(1167630))

You can skip lines in the .lua file that starts with setManifestid and lines that have no decryption key.

Now save and close that file.

(Note: usually these IDs for the DLC are in the LUA file you downloaded, if you aren't sure which ones you need, copy them from the LUA file and check them on steamdb; it'll tell you if it's a DLC or base game or some other accessory. When checking on steamdb, make sure to click DEPOT ID if it returns no APP ID.)

This is a example of the all game depots and all DLCS added from the example .lua file above:

"depots"
{
    "123456789"
    {
        "DecryptionKey" "8e4c9a10b6d5f73e2a1c08f49d7b35e6a2c90b1d4f57e3a6c8b0d29f1e47a53c"
    }
    "1167634"
    {
        "DecryptionKey" "4e8b0f273a59d1c3b762e4f8a9c5d01e2b63a7f940d58c21e7b3a69f0c4d82e1"
    }
    "2657050"
    {
        "DecryptionKey" "d17c8a2b905ef34a6c2d7b19e0f5a83c49b0d67f2e15a4c38b9f0d62e7a13c5b"
    }
    "2657080"
    {
        "DecryptionKey" "9b4e1a7c2d05f38b6e4a9c01d7f23b58a0c9e6b1d4f75a3e28c09f1b3e6d5a72"
    }
    "2657060"
    {
        "DecryptionKey" "a1d07b4e9f2c58a3e6b1d40c7f39a82e5b0c94f7a1d26e3b58c09f2e4a7b3d65"
    }
    "2657100"
    {
        "DecryptionKey" "c5b9a2d40f73e1b6a8d5c09f2e7a34b18f6d0e29c1b75a4f3e68b0d5a2c97f14"
    }                
}
Making A Fake ACF File
(A steam update in late December borked greenluma with installing games. u/TheRealRiddler121 Found a way to bypass this and make game downloading work again.)

Go to the dir C:\Program Files\Steam Luma\steamapps or C:\YOURSTEAMINSTALLATION\steamapps

Created a file called appmanifest_APPID.acf Fill in the APPID part with the game ID. Teardown would be. appmanifest_1167630.acf (Make sure it's NOT appmanifest_APPID.acf.txt)

Open that file and paste in.

    "AppState"
    {
      "AppID"  "APPID"
      "Universe" "1"
      "installdir" "APPNAME"
      "StateFlags" "1026"
    }
Once again replace APPID with the game ID. Teardown would be:

    "AppState"
    {
      "AppID"  "1167630"
      "Universe" "1"
      "installdir" "APPNAME"
      "StateFlags" "1026"
    }
Once that is done, replace APPNAME with the game's name DO NOT INCLUDE COLONS, SEMI COLONS, SLASHES, OR ANY SPECIAL CHARACTERS AS WINDOWS HATES IT. THIS WILL CAUSE A "DISK WRITE ERROR" IF YOU DO. You can also use any name or folder of your choosing for the installdir, and you do not have to create the folder beforehand.

    "AppState"
    {
      "AppID"  "1167630"
      "Universe" "1"
      "installdir" "Teardown"
      "StateFlags" "1026"
    }
Now save and close that file.

Now start steam with the DLLInjector.exe file in C:\Program Files\Steam Luma\DLLInjector.exe or C:\YOURSTEAMINSTALLATION\DLLInjector.exe.

Now to start downloading the game (Teardown) go to the steamdb game page and click install top right or run this command with Windows + R.

steam://install/APPID (Teardown app id is 1167630 so replace APPID with 1167630. Example: steam://install/1167630

And boom!! the game should start downloading

Note: if it doesn't work and you are 100% sure you did everything right then the manifest file are probably outdated or bad and you need new ones. Ryuu's generator can tell you if they are out of date or not. (If you cannot get the latest manifest files there is a section below on how to still download games with outdated manifest files)

Adding UserStats.bin Files If You Have Them
UserStats.bin files then they to go to C:\Program Files\Steam Luma\appcache\stats

How To Download Games With Outdated Manifest Files
Follow all the steps in the tutorial until you are ready to download the game

The command I will be using is download_depot <App ID> <Depot ID> <Manifest ID>

We need to fill everything in between "<>"

We know Teardowns App ID is 1167630 and the Depot ID is 1167634 (App ID can be found on the SteamDB game page and Depot ID can be found in the "Depot" section of the SteamDB game page)

So the command is looking like this now download_depot 1167630 1167634 <Manifest ID>

Now finding the Manifest ID is a little more difficult.

The Manifest ID should be in the name of the .manifest file that you downloaded from Ryuu generator. (Skip to "What do if there is multiple .manifest files?" section if there are multiple .manifest files.)

In the zip file there should be a .manifest file named something like this 1167634_2581091443668236867.manifest

The first set of numbers (1167634) is the Depot ID and the second set of numbers (2581091443668236867) is the Manifest ID.

Put the Manifest ID into the command.

Should look like this now download_depot 1167630 1167634 2581091443668236867

copy and save the command for later and skip to the "Once you got the command ready" section to download the game.

What do if there is multiple .manifest files?

You need to find the correct one to use.

Most of the time there is multiple for the dependencies and macos/linux versions of the game.

The easiest way to find which one to use is to go to the Depot section of the game page in SteamDB.

For example Stardew Valley has Windows, Macos and Linux version with dependencies listed. (https://steamdb.info/app/413150/depots/)

So look for the Windows version that's not a dependency. (dependencies have the size listed as "No size")

So the "413151 | Windows Stardew Valley Windows | 659.80 MiB | 432.68 MiB" Is the correct one.

Look for the .manfest file that starts with 413151 in the zip downloaded from Ryuu generator, the second set of numbers should be the Manifest ID. (Example: 413151_1289391404978285152.manifest)

Put the Manifest ID into the command.

Should look like this now download_depot 413150 413151 1289391404978285152

copy and save the command for later

Once you got the command ready

Press Windows key + R and paste in steam://open/console then run it.

Now go into steam and paste the download_depot command you copied earlier

The game should start downloading into the C:\Program Files\Steam Luma\steamapps\content\app_AppID\depot_DepotID or C:\YOURSTEAMINSTALLATION\steamapps\content\app_AppID\depot_DepotID

Some notes from u/Useful-Use-3296 and u/TheRealRiddler121

I am not a expert on this tool so correct me if I'm wrong on anything please.

All decryption keys seen in this tutorial are randomly generated just for tutorial purposes.

Online functionality of games don't work IF YOU DO NOT OWN THE BASE GAME.

This does not work with games that require third party game launchers.

Greenluma allows you to download games you do not own with this method if done correctly. You will probably still need to use a steam emulator and/or a steam stub DRM remover to actually play the game (IF YOU DO NOT OWN THE BASE GAME). The method I showed only downloads the game files from steam. This method does not crack games.

TROUBLESHOOTING - UPDATED 1/5/26 @ 1pm EST
"Content Still Encrypted": Bad manifest decryption key/old manifest files. Check your keys in lua and compare with the one in config.vdf.

"NO INTERNET CONNECTION": Bad/Old Manifest Files/STEAM DELETED DEPOTCACHE FILES. check and re-add the manifest files to the depotcache folder. If this doesn't work, update your manifests, one is likely out of date. You may have also missed an important depot ID in greenluma applist.

"UPDATING LOOP": See the recommendations above; it's usually one of these issues and fixes.

Game isn't showing up in list: try to install via the windows key+r command above, if you cannot because of an "unknown error." you likely have messed up somewhere along the line or your manifest files are bad or old. Please follow the guide again. Don't launch the official steam client.

"No licenses error": Did you add the correct app IDs and Depot IDs to greenluma AppList folder? Double check this, you may have missed one.

"Game download is 0 bytes":You forgot to add the game depot into the AppList folder or config.vdf file.

"DISK WRITE ERROR": You have a character in your folder name that Windows does not like. Remove it.
