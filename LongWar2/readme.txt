
Short version:
	Install Long War
	put all uFiles in your CookedPCConsole folder
	put all iniFiles in your Config folder
	patch through all .txt files with PatcherGUI (see *Note2 below)
	
	for future Updates: just overwrite the old .ini files with newer versions from 
	-> goo.gl/fkt0cc
	-> goo.gl/vBpvGZ
	-> https://www.dropbox.com/s/p8viqba8tlk89yh/DefaultStrategyAIMod.ini?dl=0
	made by Arvius (http://www.twitch.tv/anzleon)
	
How to install:

1. Install Long War: http://www.nexusmods.com/xcom/mods/88/
2. Download PatcherGUI: http://www.nexusmods.com/xcom/mods/448/
3. Use PatcherGUI to install 'XGStrategy.NewGame.txt' (Path to Steamlibary should look like this:  *\SteamApps\common\XCom-Enemy-Unknown\XEW )
4. Use PatcherGUI to install 'XGUnit.RecordKill' 
5. Copy all .u files to *\SteamApps\common\XCom-Enemy-Unknown\XEW\XComGame\CookedPCConsole 
		- replace the old files
6. Copy all .ini files to *\SteamApps\common\XCom-Enemy-Unknown\XEW\XComGame\Config 
		- replace the old files (see *Note1 below if you use other mods beside those shown here)
7. Use PatcherGUI to install 'VRmod.txt' or 'DeveloperConsole.txt' (see *Note2)
8. Use PatcherGUI to install any optional files you like
9. Play the game and suffer. (Balancing is for Impossible difficulty, recommended second wave options: #3 #8 #12 #17 #18 #29)	
10.	for future Updates: just overwrite the old .ini files with newer versions from 
	-> goo.gl/fkt0cc
	-> goo.gl/vBpvGZ
	-> https://www.dropbox.com/s/p8viqba8tlk89yh/DefaultStrategyAIMod.ini?dl=0
	made by Arvius (http://www.twitch.tv/anzleon)
	
	
	
	*Note1: If you use other mods which change DefaultEngine.ini or DefaultMutatorLoader.ini don't replace them, just add the following lines:
		Path-To-SteamLibrary\SteamApps\common\XCom-Enemy-Unknown\XEW\XComGame\Config\DefaultEngine.ini file with notepad.
		Search for this line:
		+NonNativePackages=XComLZMutator
		Add these two lines right after it:
		+NonNativePackages=XComStrategyAIMutator
		+NonNativePackages=XComSHIVXP

		Path-To-SteamLibrary\SteamApps\common\XCom-Enemy-Unknown\XEW\XComGame\Config\DefaultMutatorLoader.ini file with notepad.
		Search for:
		arrTacticalMutators="XComLZMutator.XComSpawnAlienMutator"
		Add right after it:
		arrTacticalMutators="XComSHIVXP.XComSHIVXPMutator"
		Search for:
		arrStrategicMutators="XComLZMutator.XComFCMutator"
		Add right after it:
		arrStrategicMutators="XComStrategyAIMutator.XComStrategyAIMutator"

		
		Source: https://github.com/durron597/xcom-beyond-impossible/blob/master/installation

	*Note2: Arvius currently uses the console command KillAliens in the first 
		mission because of balancing, so the first mission is meant to be skipped.
		Then in base he uses LevelUpBarracks command to increase the soldier rank by 1.
		Open devconsole with ` or ^ (depending on keyboard sttings)

		Alternatively you can use the VRmod which gives every soldier in your barracks exp per day, 
		this slowly levels all your soldiers but does not grant you 6 LCPL like the previous option.



_______________________________________________________________



Sources:

Long War: http://www.nexusmods.com/xcom/mods/88/

PatcherGUI: http://www.nexusmods.com/xcom/mods/448/

Enhanced Tactical Info: http://www.nexusmods.com/xcom/mods/554/		

Country Panic & Defense Values: http://pastebin.com/QBtsBzy2

Hit Chance: https://www.reddit.com/r/Xcom/comments/3akkhg/lw_mod_configurable_hitcrit_chance_display_for	

Customize Unique Soldier Stats: https://www.reddit.com/r/Xcom/comments/3emron/lw_customize_unique_soldier_stats/
^  http://pastebin.com/CpHHGzeE

VR Mod to auto-promote PFC to Specialists: http://pastebin.com/n80cVHnX	

Escalation Mod: http://www.nexusmods.com/xcom/mods/603/

DefaultGameCore: http://goo.gl/fkt0cc
DefaultGateData: http://goo.gl/vBpvGZ
DefaultStrategyAIMod: https://www.dropbox.com/s/p8viqba8tlk89yh/DefaultStrategyAIMod.ini?dl=0
by http://www.twitch.tv/anzleon

