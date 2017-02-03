# Ascension Pack

# Servers

1. Minecraft Main : 144.76.64.131:25565
2. Minecraft Skyblock : 144.76.64.131:25566
3. Ark Survival Evolved : 144.76.64.131:7777

# IMPORTANT
For people reinstalling please ensure you use svn or git and create a new folder following the steps below. If you feel confident you can just update your current one but i will not provide support.

# Installation

## Git

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

## Subversion (Unsuported)

1. Download the Minecraft launcher and run it. - Then close it.
2. Run stock minecraft and ensure it all works correctly.
3. Download and install TortoiseSVN from http://tortoisesvn.net/downloads.html
4. Create a folder in a place you wish to store your client files.
5. Open the folder.
6. If TortoiseSVN is installed correctly there should be a "SVN Checkout..." option
7. Click this and then enter "https://github.com/ascensionserver/ascension" in the "URL of repository"
8. Click Okay and it should begin downloading the server files inside the "trunk" folder.
9. Open the folder and install "forge-1.10.2-12.18.3.2221-installer-win.exe".
10. Launch the stock minecraft launcher again after step 8 and 9 finish.
11. Go to the Profile Editor tab.
12. Double click Forge to edit it.
13. Tick the game directory box and enter the directory you have installed your minecraft files in including the "/trunk" eg. "C:\Users\Username\Desktop\Minecraft Server\trunk"
14. Tick the JVM Arguments box and enter "-Xmx4096M -Xms4096M -XX:+UseParNewGC -XX:+UseConcMarkSweepGC -XX:+CICompilerCountPerCPU -XX:+TieredCompilation"
15. Select Save Profile
16. Ensure the correct profile is picked in the bottom left then click Play

