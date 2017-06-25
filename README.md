# Ascension Pack

# Servers

1. Minecraft Main : 144.76.64.131:25565
2. ~~Minecraft Skyblock : 144.76.64.131:25566~~
3. ~~Ark Survival Evolved : 144.76.64.131:7777.~~

# Installation
## Twitch/Curse Launcher (easiest)

### Ingredients - 
* [FTB-Beyond-Ascension](http://144.76.64.131:8082/FTB%20Beyond%20-%20Ascension-1.10.0.zip)
* [Twitch Launcher](https://app.twitch.tv/download)
* [Enable Minecraft on twitch launcher](https://help.twitch.tv/customer/en/portal/articles/2764216-how-to-play-minecraft-with-twitch-app)

### Method -
1. Go to the twitch launchers minecraft section.
2. Click 'Create Custom Profile'
3. Select 'import' (below the 'Create Profile' title at the top)
4. Select the file downloaded above (  [FTB-Beyond-Ascension](http://144.76.64.131:8082/FTB%20Beyond%20-%20Ascension-1.10.0.zip) )

## Stock launcher

### Ingredients -
* [Git](https://git-scm.com/downloads)

### Method
1. Download the Minecraft launcher and run it. - Then close it.
2. Run stock minecraft and ensure it all works correctly.
3. Download and install git: https://git-scm.com/downloads Make sure you have "Use Git from Git Bash only" option
4. Create a folder in a place you wish to store your client files.
5. Open the folder.
6. Right click in folder, and select 'Git Bash Here'
7. Type: "git clone https://github.com/ascensionserver/ascension.git" without quotes
8. Open the folder and install "forge-1.10.2-12.18.3.2221-installer-win.exe"
9. Launch the stock minecraft launcher again after step 10 finishes.
10. Go to the Profile Editor tab.
11. Double click Forge to edit it.
13. Tick the game directory box and enter the directory you have installed your minecraft files in. eg. "C:\Users\Username\Desktop\Minecraft Server"
14. Tick the JVM Arguments box and enter "-Xmx4096M -Xms4096M -XX:+UseParNewGC -XX:+UseConcMarkSweepGC -XX:+CICompilerCountPerCPU -XX:+TieredCompilation"
15. Select Save Profile
16. Ensure the correct profile is picked in the bottom left then click Play
